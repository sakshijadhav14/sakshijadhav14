!pip install translate

pip install googletrans

import googletrans as gt
print(dir(gt))

print(gt.LANGUAGES)

print(gt.LANGCODES)

from googletrans import Translator, constants
from pprint import pprint

# init the Google API translator
translator = Translator()

import numpy as np
import pandas as pd

data=pd.read_csv('song lyrics.csv')

data.describe()

data.info()

data.head()

from translate import Translator
translator= Translator(to_lang="english")
translation = translator.translate("Blackbird singing in the dead of night Take these broken wings and learn to fly All your life You were only waiting for this moment to arise")
print (translation)

from translate import Translator
translator= Translator(from_lang="english",to_lang="hindi")
translation = translator.translate("Blackbird singing in the dead of night Take these broken wings and learn to fly All your life You were only waiting for this moment to arise")
print (translation)
