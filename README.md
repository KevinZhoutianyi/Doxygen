# Doxygen



make your code in the correct format:

```cpp
//***************************************************************************************
//
//! \file class.h
//! This is a test to see how the doxygen generate the html.
//!
//! \author    Kevin
//! \version   V1.0
//! \date      2018-10-8
//
//***************************************************************************************



#ifndef CLASS_H
#define CLASS_H

#include "iostream"


#define CNT_MAX  10  //!< The maxium number of print

using namespace std;

class My_Fish
{

    private:
        int mother;
        int father;

    public:
        My_Fish(int temp1,int temp2)
        {
            cout<<"MYFISH object is created"<<endl;
            cout<<temp1<<endl;
            cout<<temp2<<endl;
            this->mother=temp1;
            this->father=temp2;
        }


};


#endif // CLASS_H

```

using doxygen you will get：

![pic](https://github.com/OnlyDrinkWater/Doxygen/blob/master/Pic_md/1.png?raw=true)

