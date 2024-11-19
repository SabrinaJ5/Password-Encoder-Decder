# Password Encoder/Decoder 🔐  

### About the Project  
This project was a lab assignment for my **Programming Fundamentals 1 class** at the **University of Florida**.  

The goal of the assignment was to create a program that can encode and decode passwords using a simple digit-shifting method. This lab demonstrated foundational programming concepts such as functions, loops, and user input handling.

---

### Project Details  
- **Author**: Sabrina Joseph  
- **Description**: Lab 4 - Password Encoder/Decoder  

---

### How It Works  
1. **Encoding**:  
   - Shifts each digit in the password up by 3.  
   - For example, a password of `1234` becomes `4567`.  

2. **Decoding**:  
   - Shifts each encoded digit back down by 3 to recover the original password.  

3. **User Interaction**:  
   - A menu-based system allows users to encode a password, decode it, or exit the program.  

---

### Code Features  
- **Functions**:  
  - `encoder(pw)`: Encodes the password by shifting each digit.  
  - `decode(password)`: Decodes the password by reversing the shift.  
  - `menu()`: Displays a user-friendly menu.  

- **Error Handling**:  
  - Handles invalid menu inputs gracefully with an error message.  

- **Example Execution**:  
   - User enters a password to encode.  
   - The program encodes it, stores it, and provides the decoded version upon request.  

---

### How to Run  
1. Clone or download this repository.  
2. Ensure Python is installed on your system.  
3. Run the program in the terminal or IDE using:  
   ```bash
   python pw_encoder_decoder.py
