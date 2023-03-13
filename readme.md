### Pi-Day

```echo "scale=10000;4*a(1)" | bc -l ```  

- `echo` is a Unix command that prints a message or output to the console.  
- "scale=10000;4*a(1)" is a string containing the bc command to calculate the value of pi. In this case, the scale variable is set to 10000, which specifies the number of decimal places to calculate, and 4*a(1) is used to calculate pi using the arctangent function.
- `|` is a Unix operator that pipes the output of one command to another command.  
- `bc` is a command-line calculator that performs floating-point arithmetic.  
- `-l` is an option for the bc command that enables the math library, including trigonometric functions like a(), which is used to calculate the arctangent function.  
  
  
When you run this command, the output will be the value of pi with 10,000 decimal places.

In summary, this command uses echo to send a message containing a bc command to calculate pi with high precision, pipes it to the bc command, and then uses the -l option to enable the math library and trigonometric functions in bc. The result is the value of pi with a specified number of decimal places printed to the console.

### See the CPU as pi is generated  

```bash
sudo powermetrics --samplers smc |grep -i "CPU die temperature"
```
* note: password is required to excute the above



### Readmore:, The Ramanujan formula for pi:  

pi ≈ 1 / (2√2 / 9801) ∑<sub>k=0</sub>^∞ (4k)!(1103+26390k) / (k!)^4 396^(4k)
where ∑ represents the sum from k=0 to infinity.

This will display the text "The Ramanujan formula for pi is:" followed by the formula for pi using the Ramanujan series. The formula is written using HTML subscripts to display the subscripts, and the summation symbol is represented using Unicode.

This markdown syntax will generate the following output:

The Ramanujan formula for pi is:

pi ≈ 1 / (2√2 / 9801) ∑<sub>k=0</sub>^∞ (4k)!(1103+26390k) / (k!)^4 396^(4k)

where ∑ represents the sum from k=0 to infinity.
