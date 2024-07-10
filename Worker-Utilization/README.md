# Web Worker Examples

This project contains examples demonstrating the use of Web Workers for performing background computations without blocking the main thread. Web Workers enable parallel processing, which is essential for handling intensive tasks in web applications.

## Prime Generation Example

This example shows how to use a Web Worker to generate a specified number of prime numbers. The main thread remains responsive, allowing users to interact with the UI while the Web Worker performs the computation.

### Files

- `index.html`: Contains the HTML structure and JavaScript code for interacting with the Web Worker.
- `generate.js`: Contains the Web Worker code for generating prime numbers.

### How It Works

1. The user inputs the number of primes to generate.
2. When the "Generate primes" button is clicked, a message is sent to the Web Worker to start generating primes.
3. The Web Worker computes the prime numbers and sends a message back to the main thread once the task is completed.
4. The main thread updates the UI to inform the user that the prime generation is complete.

### Usage

1. Open `index.html` in a web browser.
2. Enter the number of primes to generate in the input field.
3. Click the "Generate primes" button.
4. Observe that the UI remains responsive while the Web Worker performs the computation in the background.
5. The result is displayed once the computation is complete.

This example illustrates the benefits of using Web Workers for background processing, improving the overall user experience by keeping the UI responsive during intensive tasks.
