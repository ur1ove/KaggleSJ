###
~~~
(base) C:\Users\~>conda-env list
WARNING: The conda.compat module is deprecated and will be removed in a future release.
WARNING: The conda.compat module is deprecated and will be removed in a future release.
# conda environments:
#
base                  *  F:\ProgramData\Anaconda3
NLP                      F:\ProgramData\Anaconda3\envs\NLP


(base) C:\Users\~>conda activate NLP

C:\Users\~>set "JAVA_HOME_CONDA_BACKUP=C:\Program Files\Java\jdk1.8.0_211"

C:\Users\~>set "JAVA_HOME=F:\ProgramData\Anaconda3\envs\NLP\Library"

(NLP) C:\Users\~>pip install selenium
Collecting selenium
  Downloading https://files.pythonhosted.org/packages/80/d6/4294f0b4bce4de0abf13e17190289f9d0613b0a44e5dd6a7f5ca98459853/selenium-3.141.0-py2.py3-none-any.whl (904kB)
     |████████████████████████████████| 911kB 211kB/s
Requirement already satisfied: urllib3 in f:\programdata\anaconda3\envs\nlp\lib\site-packages (from selenium) (1.25.2)
Installing collected packages: selenium
Successfully installed selenium-3.141.0

(NLP) C:\Users\~>pip install selenium -U
Requirement already up-to-date: selenium in f:\programdata\anaconda3\envs\nlp\lib\site-packages (3.141.0)
Requirement already satisfied, skipping upgrade: urllib3 in f:\programdata\anaconda3\envs\nlp\lib\site-packages (from selenium) (1.25.2)

(NLP) C:\Users\~>
~~~
