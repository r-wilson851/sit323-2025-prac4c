
# Step by Step instrucions 

## 1. Added the helper functions to handle exponents, modulo & root 
- this involved using the `**` , `%`, and `Math.sqrt()` operators in the body of the functions for exponents, modulo and root, respectively
- all of the additional helper functions take 2 input parametesrs `n1, n2` just like the originals for adding, subtracing & multplying

<img width="449" alt="image" src="https://github.com/user-attachments/assets/b26db14c-7438-47a6-8764-ee3cdd1036e4" />



<br> <br> 



## 2. Added routes for each of the 3 new features `/mod` , `/root` , `/exponent`
- each route uses a `try & catch` for error handling via parsing the input parameters as `floats` and then throws errors if they're not numbers
  - the errors (if any) are then logged to the console and returned in the returned  json object with the appopriate status code (500)   
- each route calls its respective helper function with the query parameters as input parameters 
- for successful calls it returns the answer as a json object and provides a success status code (200)

<img width="568" alt="image" src="https://github.com/user-attachments/assets/fa0c9336-2b03-4e1a-8857-184a34b4aad1" />
