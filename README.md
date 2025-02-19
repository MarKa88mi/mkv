# mkv

#include <iostream>
#include <iomanip>
#include <math.h>

	using namespace std;

		int main()
		{

			double long a = 1.10101010101010, b = 1.01010101, c = 1.1010101010, d =1.2 ,m = 1.3;

			for( a; a < 1000; a++, b++, c++, d++, m++ )


			{
				a = sqrt(7);
				b = sqrt(1000);

					c = sqrt(( a + b * b * ( m - 2 )  ) / ( ( m - 1.1 ) * ( m - 2.2 ) + ( a + b + 2.1 ) ));

						d = sqrt( log(c) * log(b) + a * b * 0.1 );

							m = sqrt( ( d - c ) * ( d - c ) ) + ( ( b - a ) * ( b - a ) ) + ( a / ( b  + 1.1 ) ); 


					cout << setprecision(100) << "\t\tc:::[" << c << "]" << "\t\t[m:::" << m  << "]" << "\t\t[d:::" << d << "]" <<  "\t\t[c:::" << c << "]";
			}

				

		}
