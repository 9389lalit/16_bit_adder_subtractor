# 16_bit_adder_subtractor
It's a calculator to find the sum and subtraction in 2's complement of 2 16 bit number

Circuit for the 16 bit adder and Subtractor 
![image](https://github.com/9389lalit/16_bit_adder_subtractor/assets/99964550/edb1daa0-63c7-4fa2-b367-350553ea1591)

# Adder 
To use the circuit as a adder give the adder/subtractor pin value as 0 and as we know the xor of 0 and any number is the number itself so we will get the number B itself and also the cin is 0 so after adding the bits you can see the output in the 7 segment displays.
In case of overflow  you can see the extra cassy bit as high.

![image](https://github.com/9389lalit/16_bit_adder_subtractor/assets/99964550/7b5a874e-edd4-41f4-8094-9de5ecb06a99)

# Subtractor 
To use the circuit as a subtractor use adder/subtractor pin as 1 and 1^B=B' and cin=1 so after addition we will get the subtraction but as if the carry is high then the answer will remain the same but in case of carry bit as 0 we will again change the number in 
2's complement

2's complement circuit

![image](https://github.com/9389lalit/16_bit_adder_subtractor/assets/99964550/6f71f0f0-4f30-4f1a-9be0-c5745c8a75f7)

You can see the final output at 7 segment displays

![Uploading image.png…]()
