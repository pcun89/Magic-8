
 **Magic 8-Ball Simulation in Python**

This Python script simulates the Magic 8-Ball, offering users playful and random responses to their questions. Additionally, a unit test has been included to ensure the functionality of key components. Follow the guide below to explore the Magic 8-Ball simulation:

### Usage Instructions:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/magic-8-ball-simulation.git
   cd magic-8-ball-simulation
   ```

2. **Run the Simulation:**
   ```bash
   python magic_8_ball.py
   ```
   - Enter your name and ask a question to receive a whimsical response from the Magic 8-Ball.

### Unit Test:

A unit test has been included to validate the correctness of the script. Run the following command to execute the test:

```bash
python Test.py
```

This test ensures that critical functions, such as user input gathering and response generation, function as expected.

### Script Overview:

- **User Input Function:**
  - The `get_user_input` function prompts the user to enter their name and ask a question to the Magic 8-Ball.

- **Response Generation Function:**
  - The `generate_response` function randomly selects a response from a predefined list of answers commonly found in a Magic 8-Ball.

- **Magic 8-Ball Response Function:**
  - The `magic_8_ball_response` function utilizes the user input function to gather information.
  - It checks if the name and question are provided; otherwise, it prompts the user to provide both.
  - The function then generates a random response using the response generation function and displays the user's question, along with the Magic 8-Ball's answer.

### Running Unit Test:

Ensure the unit test validates the correct functionality of the script components.

Feel free to experiment, enhance, and contribute to the Magic 8-Ball simulation!
