
#include <iostream>
using namespace std;

/*
return array function test program.
very simple way.
1D, 2D, 3D array test complete. 

TODO: 
Using Class and Template,
string array,
making Linear Algebra Function.
*/

int *arrayReturn1D(void);
void arrayPrint1D(int *array);

int (*arrayReturn2D(void))[3];
void arrayPrint2D(int (*array)[3]);

int (*arrayReturn3D(void))[3][3];
void arrayPrint3D(int (*array)[3][3]);



int main(void){

  cout << "## Array Return Library! ## " << endl;
  cout << "Let's get start!"<< endl;
  
  int *array1;
  array1=arrayReturn1D();
  arrayPrint1D(array1);


  int (*array2)[3];
  array2=arrayReturn2D();
  arrayPrint2D(array2);

  int (*array3)[3][3];
  array3=arrayReturn3D();
  arrayPrint3D(array3);

  
  cout << endl;  
  cout <<"## Main is Done!!## " <<endl;
  cout <<"#######     Nice program    ############"<< endl;
}


int *arrayReturn1D(void)
{
  cout << endl;
  cout << "## 1D Array Initialize Function ##"<< endl;
  
  static int array[3] = {1,2,3};
  
  //int arraySize = sizeof(array)/sizeof(int);

  cout << "Array Init Function is Done!" << endl;
  cout << endl;
  
  return array;
}

void arrayPrint1D(int *array)
{
  
  cout << "## 1D Array Print Function ##"<< endl;

  //int arraySize = sizeof(array)/sizeof(array[0]);
  
  for( int i=0; i< 3; i++)
  {
    cout << "array[" << i << "] : ";
    cout << array[i]<< ", ";
  }

  cout << endl;
  cout << "Array Print Function is Done!" << endl;
  cout << endl;
}


int (*arrayReturn2D(void))[3]
{
  cout << endl;
  cout << "## 2D Array Initialize Function ##"<< endl;
  
  static int array[3][3] = {{1,2,3},
			    {2,3,4},
			    {3,4,5} };
  
  //int arraySize = sizeof(array)/sizeof(int);

  cout << "2D Array Init Function is Done!" << endl;
  cout << endl;
  
  return array;

}

void arrayPrint2D(int (*array)[3])
{
  cout << "## 2D Array Print Function ##"<< endl;

  //int arraySize = sizeof(array)/sizeof(array[0]);
  
  for( int i=0; i< 3; i++)
  {
    for( int j=0; j< 3; j++)
      {
	cout << "array[" << i <<"]"<<"["<< j <<"]"<<" : ";
	cout << array[i][j]<< ", ";
      }
    cout << endl;
  }

  cout << "2D Array Print Function is Done!" << endl;
  cout << endl;
}
  

int (*arrayReturn3D(void))[3][3]
{
  cout << endl;
  cout << "## 3D Array Initialize Function ##"<< endl;
  
  static int array[3][3][3] = {{{1,2,3},
				{2,3,4},
				{3,4,5} },
			       {{4,5,6},
				{5,6,7},
				{6,7,8} },
			       {{7,8,9},
				{8,9,10},
				{11,12,13} } };
  
  //int arraySize = sizeof(array)/sizeof(int);

  cout << "3D Array Init Function is Done!" << endl;
  cout << endl;
  
  return array;

}

void arrayPrint3D(int (*array)[3][3])
{
  
  for( int i=0; i< 3; i++)
  {
    for( int j=0; j< 3; j++)
      {
	for( int k=0; k<3; k++)
	  {
	    cout << "array[" << i <<"]"<<"["<< j <<"]"<<"["<< k <<"]"<<" : ";
	    cout << array[i][j][k]<< ", ";
	  }
	cout << endl;
      }
    cout << endl;
  }

}
