VG101 Assignment3

Last Edited Date: 2018/6/7

Contributers:
    Shi Li 	517370910032
    Wang Tianyi	517370910160
    Liu Zhiyuan 51731091240
    Yuan Yin 	517370910260



Ex.1 - Accurate calculations

Output:
    Total number of grains of wheat: 18446744073709551615

Notes:
    We use the formula 2^0+2^1+...+2^63=2^64-1.
    Also, we can also use the function 'sym' in MATLAB, which was introduced by the strongest LYH in Monday's lab. sym(2^64-1)=18446744073709551615.



Ex.2 - Algorithm
    The matlab structure uses ��struct��in matlab and creates a table to summarize the wardrobe
    inventory having three indexes: Type, Color and Quantity. By comparing the quantity using ��max��
    matlab can output which item (Type+Color) has the largest quantity.It can also calculate out the 
    average years of these items.



Ex.3 - Input and output

Input format:
    An integer.
Output format:
    All the multiples n * i, 0 <= i <= 10. The output can be found in 'Ex3_Output.txt'. See the problem description of Ex.3.

Example input:
    Ex3(23)
Example output:
    See 'Ex3_Output.txt'.



Ex.4 - Ploting

Output:
    An image including a pretty house and a red Volkswagen Beetle car.



Ex.5 - Algorithm, function, conditional statements, and loops

Input format:
    a function(f), an interval(a,b),error(error)
Output format:
    'the root is xxx'
    
Example input:
    Ex5(@(x)x^2+2*x-5,1,2,0.001)
Example output:
    the root is 1.449463
    


Ex.6 - Input and output

Input format:
    A positive integer n. (Better if 2 <= n <= 16)
Output format:
    n lines of Pascal's triangle in 'Ex6_Output.txt'. See the problem description of Ex.6.

Example input:
    Ex6(6)
Example output:
    See 'Ex6_Output.txt'.

Bugs:
    The maximum length for all the figures should be equal to or less than 7. If the length is equal to or greater than 8, the program cannot handle it, and the output txt file can be unreadable.