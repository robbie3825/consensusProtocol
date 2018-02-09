
# -*- coding: utf-8 -*-
"""
Created on Tue May  9 15:14:52 2017
@author: Robbie Cunningham

"""


#preliminaries

import numpy as np
import matplotlib.pyplot as plt
import scipy as sci
from mpl_toolkits.mplot3d import Axes3D




# """parameters"""

#number of agents
N=10
#which graph?
graph = 'path'
#final time
T=10
#time incriment
j=.1
#optimality gain
a=1
#consensus gain
b=1
#saturation bound (Delta)
D=20
#dimension, either 2 or 3
m=2


