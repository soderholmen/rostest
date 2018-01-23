#!/usr/bin/env python

PKG = 'test'
import roslib; roslib.load_manifest(PKG)
import unittest 
#from test.py import my_func

class CaseA(unittest.TestCase):
    def runTest(self):
        my_var=True
        
        self.assertTrue(my_var)

if __name__ == '__main__':
    import rostest
    rostest.rosrun(PKG, 'test_bare', CaseA)
