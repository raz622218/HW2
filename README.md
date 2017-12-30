{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Welcome to Python"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Based on: http://www.scipy-lectures.org/"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 4,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<img src=\"https://qph.ec.quoracdn.net/main-qimg-57d110580af8b0196601be5fb58c96fa-c?convert_to_webp=true\"/>"
      ],
      "text/plain": [
       "<IPython.core.display.Image object>"
      ]
     },
     "execution_count": 4,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "from IPython.display import Image\n",
    "from IPython.core.display import HTML \n",
    "Image(url= \"https://qph.ec.quoracdn.net/main-qimg-57d110580af8b0196601be5fb58c96fa-c?convert_to_webp=true\")\n",
    "#Image(url=\"http://malwaredoc.com/wp-content/uploads/2014/05/shutterstock_python_0.jpg\")"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Markup"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 1,
   "metadata": {},
   "outputs": [],
   "source": [
    "# Insert a Markup text here"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": []
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Setups"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Try Jupyter (IPYTHON)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "**IPython**, an advanced **Python shell** http://ipython.org/\n",
    " \n",
    "To try it on the web, use:  https://try.jupyter.org/\n",
    "\n",
    "To learn more about Jupyter: http://jupyter.org/"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Installing Python & Jupyter using Anaconda and conda"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "1. **Download Anaconda.** Downloading Anaconda’s latest Python 3 version (currently Python 3.5).\n",
    "2. Install the version of Anaconda, which you downloaded.\n",
    "3. Congratulations, you have installed Python and Jupyter Notebook. To run the notebook (from command line):\n",
    "    - jupyter notebook"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "For more advanced programing you may need another interface. Try pyCharm."
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Data Science with Python"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "We will use the Python language, with some additional building blocks:\n",
    "- **Numpy:** provides powerful numerical arrays objects, and routines to manipulate them. http://www.numpy.org/ \n",
    "- **Scipy:** high-level data processing routines. Optimization, regression, interpolation, etc http://www.scipy.org/\n",
    "- **Matplotlib:** 2-D visualization,“publication-ready” plots http://matplotlib.org/\n",
    "- **pandas:** providing high-performance, easy-to-use data structures and data analysis tools http://pandas.pydata.org/\n",
    "- **scikit-learn:** simple and efficient tools for data mining and data analysis http://scikit-learn.org/stable/\n",
    "- **Statsmodels:** provides a complement to scipy for statistical computations including descriptive statistics and data exploration, statistical models, and statistical tests. http://statsmodels.sourceforge.net/"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Set your working directory"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "#### Where am I?"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 2,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'/home/jovyan'"
      ]
     },
     "execution_count": 2,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "import os\n",
    "os.getcwd()"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "#### Change a directory:"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "cd ~/"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "cd C:/Users/ofrit/Dropbox/Teaching/Technion/sandbox "
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "#### A better idea:"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "1. Create Jupyter's shortcut in your working directory\n",
    "2. Right click it to get into Properties\n",
    "3. Set Target to *jupyter notebook* and Start in to the full path of your new working directory. Aprove the new settings.\n",
    "4. Launch jupyter using your new shortcut.\n",
    "\n",
    "Or follow: http://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/execute.html#change-jupyter-notebook-startup-folder-windows"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Let's start working"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 3,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Hello Python\n"
     ]
    }
   ],
   "source": [
    "print('Hello Python') #shift+enter to run this chunk and move to the next one"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Getting help by using the ? operator after an object:"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 4,
   "metadata": {},
   "outputs": [],
   "source": [
    "print?"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### Run a script "
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Create a ﬁle script1.py in a text editor. In the ﬁle, add the following lines: "
   ]
  },
  {
   "cell_type": "raw",
   "metadata": {},
   "source": [
    "s = 'Hello world' \n",
    "print(s)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Now run your script:"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 5,
   "metadata": {},
   "outputs": [
    {
     "name": "stderr",
     "output_type": "stream",
     "text": [
      "ERROR:root:File `'script1.py'` not found.\n"
     ]
    }
   ],
   "source": [
    "%run script1.py "
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Explore the resulting variables: "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 6,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Variable   Type      Data/Info\n",
      "------------------------------\n",
      "os         module    <module 'os' from '/opt/c<...>nda/lib/python3.6/os.py'>\n"
     ]
    }
   ],
   "source": [
    "%whos"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "**From a script to functions:** plan the script as a set of reusable functions, instead of a ﬁle full of instructions following each other."
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Basics"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 7,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "int"
      ]
     },
     "execution_count": 7,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "a = 3\n",
    "b = 2*a\n",
    "type(b)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 8,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "6\n"
     ]
    }
   ],
   "source": [
    "print(b)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 9,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "18"
      ]
     },
     "execution_count": 9,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "a*b"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 10,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "str"
      ]
     },
     "execution_count": 10,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "b = 'hello' \n",
    "type(b)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 11,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'hellohello'"
      ]
     },
     "execution_count": 11,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "b + b"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 12,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'hellohello'"
      ]
     },
     "execution_count": 12,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "b*2"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Exercise 1: first steps "
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "1. Load the materials of this class into a folder. Create a shortcut to Jupyter and put it in your folder. Set Target and start in properties to change the starting working directory.\n",
    "2. Create a new Python notebook (we will go with conda root).\n",
    "3. Add a new metadata chunk, and describe your next step there. (if you prefer key commands: b for adding a chunk below, m for converting it to metadata)\n",
    "4. Add a new code chunk and print your name.(shift+ enter to run to the next chunk)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 13,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Raz Amitzur\n"
     ]
    }
   ],
   "source": [
    "print('Raz Amitzur')"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Basic Types and Arithmetic Operations "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 14,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "2"
      ]
     },
     "execution_count": 14,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "#integer:\n",
    "1 + 1"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 15,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "int"
      ]
     },
     "execution_count": 15,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "a = 4\n",
    "type(a)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 16,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "float"
      ]
     },
     "execution_count": 16,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "#Float:\n",
    "c = 2.1\n",
    "type(c)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "#complex\n",
    "a = 1.5 + 0.5j\n",
    "a.real"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "a.imag"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "type(1. + 0j) "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "#Boolean\n",
    "3 > 4"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "test = (3 > 4) \n",
    "test"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "type(test)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "#Tobesafe: useﬂoats (Python2 returns 2)\n",
    "7 / 3."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "2**10 "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "#modulo:\n",
    "8 % 3 "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "float(1)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Containers"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### List"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "A list is an ordered collection of objects, that may have different types. For example: "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 17,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "list"
      ]
     },
     "execution_count": 17,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "l = ['red', 'blue', 'green', 'black', 'white'] \n",
    "type(l)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Python's indices starts at 0, not at 1 (like at R). \n",
    "\n",
    "Access elements by index:"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 18,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'green'"
      ]
     },
     "execution_count": 18,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "l[2]"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 19,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'white'"
      ]
     },
     "execution_count": 19,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "l[-1] "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 20,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'black'"
      ]
     },
     "execution_count": 20,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "l[-2] "
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "The range **start:stop** means: start<= index **<** stop "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 21,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "['green', 'black']"
      ]
     },
     "execution_count": 21,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "l[2:4]"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "**Slicing syntax:** l[start:stop:stride]\n",
    "\n",
    "All slicing parameters are optional:"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 22,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "['black', 'white']"
      ]
     },
     "execution_count": 22,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "l[3:]"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 23,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "['red', 'blue', 'green']"
      ]
     },
     "execution_count": 23,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "l[:3]"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 24,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "['red', 'green', 'white']"
      ]
     },
     "execution_count": 24,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "l[::2]"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Lists are mutable objects and can be modiﬁed: "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 25,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "['yellow', 'blue', 'green', 'black', 'white']"
      ]
     },
     "execution_count": 25,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "l[0] = 'yellow' \n",
    "l"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "l[2:4] = ['gray', 'purple'] \n",
    "l"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "The elements of a list may have different types"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 26,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "[3, -200, 'hello']"
      ]
     },
     "execution_count": 26,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "l = [3, -200, 'hello'] \n",
    "l"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 27,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "(-200, 'hello')"
      ]
     },
     "execution_count": 27,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "l[1],l[2]"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "For collections of numerical data that all have the same type, it is often more efﬁcient to use the array type provided by the numpy module. A NumPy array is a chunk of memory containing ﬁxed-sized items. With NumPy arrays, operations on elements can be faster because elements are regularly spaced in memory and more operations are performed through specialized C functions instead of Python loops."
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Add and remove list elements: "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 28,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "['red', 'blue', 'green', 'black', 'white', 'pink']"
      ]
     },
     "execution_count": 28,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "l = ['red', 'blue', 'green', 'black', 'white'] \n",
    "l.append('pink') \n",
    "l"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 29,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'pink'"
      ]
     },
     "execution_count": 29,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "l.pop()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 30,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "['red', 'blue', 'green', 'black', 'white']"
      ]
     },
     "execution_count": 30,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "l"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 31,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "['red', 'blue', 'green', 'black', 'white', 'pink', 'purple']"
      ]
     },
     "execution_count": 31,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "l.extend(['pink', 'purple']) # extend l, in-place\n",
    "l"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 32,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "['red', 'blue', 'green', 'black', 'white']"
      ]
     },
     "execution_count": 32,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "l = l[:-2] \n",
    "l"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 33,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "['white', 'black', 'green', 'blue', 'red']"
      ]
     },
     "execution_count": 33,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "#reverse:\n",
    "r = l[::-1]\n",
    "r"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Concatenate and repeat lists:"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 34,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "['white',\n",
       " 'black',\n",
       " 'green',\n",
       " 'blue',\n",
       " 'red',\n",
       " 'red',\n",
       " 'blue',\n",
       " 'green',\n",
       " 'black',\n",
       " 'white']"
      ]
     },
     "execution_count": 34,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "r + l"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 35,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "['white',\n",
       " 'black',\n",
       " 'green',\n",
       " 'blue',\n",
       " 'red',\n",
       " 'white',\n",
       " 'black',\n",
       " 'green',\n",
       " 'blue',\n",
       " 'red']"
      ]
     },
     "execution_count": 35,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "r*2"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 36,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "['black', 'blue', 'green', 'red', 'white']"
      ]
     },
     "execution_count": 36,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "#Sort: \n",
    "sorted(r) # new object"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 37,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "['white', 'black', 'green', 'blue', 'red']"
      ]
     },
     "execution_count": 37,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "r"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 38,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "['black', 'blue', 'green', 'red', 'white']"
      ]
     },
     "execution_count": 38,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "r.sort() # in-place \n",
    "r"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "The notation r.method() (e.g. r.append(3) and L.pop()) is our ﬁrst example of object-oriented programming(OOP).Being a list, the object r owns the method function that is called using the notation ."
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Discovering methods:\n",
    "in Ipython: tab-completion (press tab) "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 39,
   "metadata": {},
   "outputs": [
    {
     "ename": "SyntaxError",
     "evalue": "invalid syntax (<ipython-input-39-4f135f8bb41d>, line 1)",
     "output_type": "error",
     "traceback": [
      "\u001b[0;36m  File \u001b[0;32m\"<ipython-input-39-4f135f8bb41d>\"\u001b[0;36m, line \u001b[0;32m1\u001b[0m\n\u001b[0;31m    r.<TAB>\u001b[0m\n\u001b[0m      ^\u001b[0m\n\u001b[0;31mSyntaxError\u001b[0m\u001b[0;31m:\u001b[0m invalid syntax\n"
     ]
    }
   ],
   "source": [
    "r.<TAB>"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 40,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "[1, 2, 3, 4]"
      ]
     },
     "execution_count": 40,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "t = [1,2,3,4]\n",
    "t"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 41,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "['1', '2', '3', '4']"
      ]
     },
     "execution_count": 41,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "#apply a method to each element in the list using \"map\"\n",
    "list(map(str,t))"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Strings"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 42,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'Hello, how are you?'"
      ]
     },
     "execution_count": 42,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "s = 'Hello, how are you?' \n",
    "s"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 43,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "\"Hi, what's up\""
      ]
     },
     "execution_count": 43,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "s = \"Hi, what's up\" \n",
    "s"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 44,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "\"Hi, what's \\n        up?\""
      ]
     },
     "execution_count": 44,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "# tripling the quotes allows the string to span more than one line \n",
    "s = \"\"\"Hi, what's \n",
    "        up?\"\"\"\n",
    "s"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 45,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'Hello, \\n        how are you'"
      ]
     },
     "execution_count": 45,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "s = '''Hello, \n",
    "        how are you''' \n",
    "s"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Strings are collections like lists. Hence they can be indexed and sliced, using the same syntax and rules."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 46,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'h'"
      ]
     },
     "execution_count": 46,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "a = \"hello, world!\"\n",
    "a[0] "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 47,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'lo,'"
      ]
     },
     "execution_count": 47,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "a[3:6] # 3rd to 6th (excluded) elements: elements 3, 4, 5 "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 48,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'lo o'"
      ]
     },
     "execution_count": 48,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "a[2:10:2] # Syntax: a[start:stop:step] "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 49,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'hl r!'"
      ]
     },
     "execution_count": 49,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "a[::3] # every three characters, from beginning to end "
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "A string is an immutable object and it is not possible to modify its contents. One may however create new strings from the original one. "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 50,
   "metadata": {},
   "outputs": [
    {
     "ename": "TypeError",
     "evalue": "'str' object does not support item assignment",
     "output_type": "error",
     "traceback": [
      "\u001b[0;31m---------------------------------------------------------------------------\u001b[0m",
      "\u001b[0;31mTypeError\u001b[0m                                 Traceback (most recent call last)",
      "\u001b[0;32m<ipython-input-50-48baa5bb0b8d>\u001b[0m in \u001b[0;36m<module>\u001b[0;34m()\u001b[0m\n\u001b[0;32m----> 1\u001b[0;31m \u001b[0ma\u001b[0m\u001b[0;34m[\u001b[0m\u001b[0;36m2\u001b[0m\u001b[0;34m]\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0;34m'z'\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m",
      "\u001b[0;31mTypeError\u001b[0m: 'str' object does not support item assignment"
     ]
    }
   ],
   "source": [
    "a[2] = 'z' "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 51,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'hezlo, world!'"
      ]
     },
     "execution_count": 51,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    " a.replace('l', 'z', 1) "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 52,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'hezzo, worzd!'"
      ]
     },
     "execution_count": 52,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    " a.replace('l', 'z') "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 53,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'An integer: 1; a float: 0.100000; another string: string'"
      ]
     },
     "execution_count": 53,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "#String formatting:\n",
    "'An integer: %i; a float: %f; another string: %s' % (1, 0.1, 'string') "
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Exercise 2: Lists"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "1. Create a list with seven numbers.\n",
    "2. Create another list in reverse order, ignoring the first two elements.\n",
    "3. Now use the last list, and check for the number that appears third in the list. (if it's a seven, print 'boom' ;-)  )"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 57,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "[4, 3, 2, 1]"
      ]
     },
     "execution_count": 57,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "L1=[1,2,3,4,5,6,7]\n",
    "L2=L1[::-1]\n",
    "L3=L2[3:7]\n",
    "L3"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 75,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "2"
      ]
     },
     "execution_count": 75,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "L3[2]"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 74,
   "metadata": {},
   "outputs": [],
   "source": [
    "if L3[2]==7:\n",
    " print('boom')"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Dictionaries:"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "A dictionary is basically an efﬁcient table that maps keys to values. It is an unordered container "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 76,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "{'emmanuelle': 5752, 'francis': 5915, 'sebastian': 5578}"
      ]
     },
     "execution_count": 76,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "tel = {'emmanuelle': 5752, 'sebastian': 5578} \n",
    "tel['francis'] = 5915 \n",
    "tel"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 77,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "5578"
      ]
     },
     "execution_count": 77,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "tel['sebastian'] "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 78,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "dict_keys(['emmanuelle', 'sebastian', 'francis'])"
      ]
     },
     "execution_count": 78,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "tel.keys() "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 79,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "dict_values([5752, 5578, 5915])"
      ]
     },
     "execution_count": 79,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "tel.values() "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 80,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "True"
      ]
     },
     "execution_count": 80,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "'francis' in tel "
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "It can be used to conveniently store and retrieve values associated with a name. \n",
    "A dictionary can have keys with different types: "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 81,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "{3: 'hello', 'a': 1, 'b': 2}"
      ]
     },
     "execution_count": 81,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "d = {'a':1, 'b':2, 3:'hello'} \n",
    "d"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Tuples"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Tuples are basically immutable lists. The elements of a tuple are written between parentheses,or just separated by commas: "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 82,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "(12345, 54321, 'hello!')"
      ]
     },
     "execution_count": 82,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "t = 12345, 54321, 'hello!' \n",
    "t"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 83,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "12345"
      ]
     },
     "execution_count": 83,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "t[0]"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 84,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "(12345, 'hello!')"
      ]
     },
     "execution_count": 84,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "t = (12345, 'hello!' )\n",
    "t"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Sets"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Unordered, unique items: "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 85,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "{'a', 'b', 'c'}"
      ]
     },
     "execution_count": 85,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "s = set(('a', 'b', 'c', 'a')) \n",
    "s"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 86,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "{'c'}"
      ]
     },
     "execution_count": 86,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "s.difference(('a', 'b')) "
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Things to note:"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "A single object can have several names bound to it: "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 87,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "[1, 2, 3]"
      ]
     },
     "execution_count": 87,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "a = [1, 2, 3] \n",
    "b = a\n",
    "b"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 88,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "True"
      ]
     },
     "execution_count": 88,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "a is b"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 89,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "[1, 'hi!', 3]"
      ]
     },
     "execution_count": 89,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "b[1] = 'hi!' \n",
    "a"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 90,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "140643815227144"
      ]
     },
     "execution_count": 90,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "id(a)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 91,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "140643815227144"
      ]
     },
     "execution_count": 91,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "id(b)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 92,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "140643815197000"
      ]
     },
     "execution_count": 92,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "# Creates another object\n",
    "a=['a','b','c']\n",
    "id(a)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Mutable objects can be changed in place (while immutable objects cannot be modiﬁed once created)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 93,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "140643815197000"
      ]
     },
     "execution_count": 93,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "# Modifies object in place:\n",
    "a[:]= [1,2,3]\n",
    "id(a)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "#  Control Flow"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "**Be careful to respect the indentation depth.** Blocks are delimited by indentation."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 94,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Obvious!\n"
     ]
    }
   ],
   "source": [
    "if 2**2 == 4: \n",
    "    print('Obvious!')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 95,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "A lot\n"
     ]
    }
   ],
   "source": [
    "a = 10\n",
    "if a == 1:\n",
    "    print(1)\n",
    "elif a == 2:\n",
    "    print(2)\n",
    "else:\n",
    "    print('A lot') "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 96,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "0\n",
      "1\n",
      "2\n",
      "3\n"
     ]
    }
   ],
   "source": [
    "for i in range(4):\n",
    "    print(i) "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 97,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Python is cool\n",
      "Python is powerful\n",
      "Python is readable\n"
     ]
    }
   ],
   "source": [
    "for word in ('cool', 'powerful', 'readable'):\n",
    "    print('Python is %s' % word) "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 98,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "677"
      ]
     },
     "execution_count": 98,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "z = 2\n",
    "while abs(z) < 100:\n",
    "    z = z**2 + 1\n",
    "z "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 99,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "(0, 'cool')\n",
      "(1, 'powerful')\n",
      "(2, 'readable')\n"
     ]
    }
   ],
   "source": [
    "#iterate over a sequence while keeping track of the item number:\n",
    "words = ('cool', 'powerful', 'readable') \n",
    "for index, item in enumerate(words):\n",
    "    print((index, item)) "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 100,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Key: a has value: 1\n",
      "Key: b has value: 1.2\n",
      "Key: c has value: True\n"
     ]
    }
   ],
   "source": [
    "#Looping over a dictionary:\n",
    "d = {'a': 1, 'b': 1.2, 'c': True}\n",
    "for key, val in sorted(d.items()):\n",
    "    print('Key: %s has value: %s' % (key, val)) "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 101,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "[0, 1, 4, 9]"
      ]
     },
     "execution_count": 101,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "# List Comprehensions\n",
    "[i**2 for i in range(4)] "
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Defining functions"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 102,
   "metadata": {},
   "outputs": [],
   "source": [
    "def test():\n",
    "    print('in test function') "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 103,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "in test function\n"
     ]
    }
   ],
   "source": [
    "test() "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 104,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "7.0649999999999995"
      ]
     },
     "execution_count": 104,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "def disk_area(radius):\n",
    "    return 3.14 * radius * radius \n",
    "\n",
    "disk_area(1.5) "
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "By default, functions return None.\n",
    "\n",
    "Mandatory parameters:"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "disk_area() #a missing parameter"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "#Optional parameters (Keyword arguments allow you to specify default values.)\n",
    "def disk_area(radius=2):\n",
    "    return 3.14 * radius * radius \n",
    "\n",
    "disk_area() "
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Default values are evaluated when the function is deﬁned, not when it is called. This can be problematic when using mutable types (e.g. dictionary or list) and modifying them in the function body, since the modiﬁcations will be persistent across invocations of the function. "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "bigx = 10\n",
    "def double_it(x=bigx):\n",
    "    return x * 2\n",
    "\n",
    "bigx = 1e9 # Now really big\n",
    "double_it() "
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Using a mutable type in a keyword argument (and modifying it inside the function body): "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "def add_to_dict(args={'a': 1, 'b': 2}): \n",
    "    for i in args.keys(): \n",
    "        args[i] += 1 \n",
    "    print(args)\n",
    "        \n",
    "add_to_dict()\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "add_to_dict() "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "add_to_dict() "
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Parameters to functions are references to objects, which are passed by value. When you pass a variable to a function, python passes the reference to the object to which the variable refers (the value). Not the variable itself. If the value passed in a function is immutable, the function does not modify the caller’s variable. If the value is mutable,the function may modify the caller’s variable in-place: "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "def try_to_modify(x, y, z):\n",
    "    x = 23\n",
    "    y.append(42)\n",
    "    z = [99] # new reference \n",
    "    print(x) \n",
    "    print(y) \n",
    "    print(z) \n",
    "    \n",
    "a = 77 # immutable variable\n",
    "b = [99] # mutable variable \n",
    "c = [28] \n",
    "try_to_modify(a, b, c) "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "print(a) "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "print(b) "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "print(c)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Functions have a local variable table called a local namespace. \n",
    "The variable x only exists within the function try_to_modify."
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "#### Global variables"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Variables declared outside the function can be referenced within the function: "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "x = 5\n",
    "def addx(y):\n",
    "    return x + y\n",
    "addx(10)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "But these “global” variables cannot be modiﬁed within the function, unless declared global in the function.\n",
    "This doesn’t work: "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "x = 5\n",
    "def setx(y):\n",
    "    x = y\n",
    "    print('x is %d' % x)\n",
    "    \n",
    "setx(10) "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "x"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "This works:"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "x=5\n",
    "def setx(y):\n",
    "    global x \n",
    "    x = y \n",
    "    print('x is %d' % x)\n",
    "    \n",
    "setx(10) "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "x"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "#### Variable number of parameters"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "**Special forms of parameters:**\n",
    "    - *args: any number of positional arguments packed into a tuple \n",
    "    - **kwargs: any number of keyword arguments packed in to a dictionary"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "def variable_args(*args, **kwargs):\n",
    "    \"\"\"Concise one-line sentence describing the function.\n",
    "    Extended summary which can contain multiple paragraphs.\n",
    "    \"\"\"\n",
    "    print('args is', args)\n",
    "    print('kwargs is', kwargs)\n",
    "    \n",
    "variable_args('one', 'two', x=1, y=2, z=3) "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "#see the docstring when searching for help with this function\n",
    "variable_args?"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Functions are ﬁrst-class objects, which means they can be assigned to a variable.\n",
    "Methods are functions attached to objects. "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "va = variable_args\n",
    "va('three', x=1, y=2) "
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Exercise 3: Fibonacci sequence"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {
    "collapsed": true
   },
   "source": [
    "Write a function that displays the n ﬁrst terms of the Fibonacci sequence, deﬁned by: \n",
    "    - u_0 = 1; u_1 = 1 \n",
    "    - u_(n+2) = u_(n+1) + u_n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 111,
   "metadata": {
    "scrolled": true
   },
   "outputs": [
    {
     "data": {
      "text/plain": [
       "2"
      ]
     },
     "execution_count": 111,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "u_0 = 1\n",
    "u_1 = 1\n",
    "u_2=u_1 + u_0\n",
    "u_2"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 114,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "3"
      ]
     },
     "execution_count": 114,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "u_3=u_2+u_1\n",
    "u_3"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### Importing objects from modules "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "import numpy as np # data arrays \n",
    "np.linspace(0, 10, 6) "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "import scipy # scientific computing"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "###  Creating modules"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "If we want to write larger and better organized programs (compared to simple scripts), where some objects are deﬁned, (variables, functions, classes) and that we want to reuse several times, we have to create our own modules. \n",
    "Let us create a module demo contained in the ﬁle demo.py: "
   ]
  },
  {
   "cell_type": "raw",
   "metadata": {},
   "source": [
    "\"A demo module.\"\n",
    "\n",
    "def print_b():\n",
    "    \"Prints b.\"\n",
    "    print('b')\n",
    "    \n",
    "def print_a(): \n",
    "    \"Prints a.\"\n",
    "    print('a')\n",
    "\n",
    "c = 2 \n",
    "d = 2 "
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "In this ﬁle, we deﬁned two functions print_a and print_b. Suppose we want to call the print_a function from the interpreter. We could execute the ﬁle as a script, but since we just want to have access to the function print_a, we are rather going to import it as a module. The syntax is as follows. "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "import demo\n",
    "demo.print_a() "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "demo.print_b()"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Modules are cached: if you modify demo.py and re-import it in the old session, you will get the old one. Solution: "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "import importlib\n",
    "importlib.reload(demo)"
   ]
  }
 ],
 "metadata": {
  "anaconda-cloud": {},
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.6.3"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 1
}
