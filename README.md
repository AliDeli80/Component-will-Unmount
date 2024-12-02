# Hide and Show Clock  

A simple React application to display a clock that can be shown or hidden. The clock updates every second and is rendered using `componentDidMount` and cleaned up with `componentWillUnmount` to manage the time interval effectively.   

## Features  

- Displays the current time that updates every second.  
- Provides functionality to hide or show the clock.  
- Uses React lifecycle methods for efficient resource management.  

## Technologies Used  

- React  
- JavaScript  
- HTML/CSS

## Installation  

To use this project locally, follow these steps:  

1. **Clone the repository**:  
```bash  
git clone https://github.com/AliDeli80/Hide-and-Show-Clock.git  
cd hide-and-show-clock
```
2. **Install dependencies**:
```bash
npm install
```
3. **Run the application**:
```bash
npm start
```
This will start the React application on http://localhost:3000.

## Usage

Once the application is running, you will see a button to toggle the visibility of the clock. The clock shows the current time and updates every second when visible.

## Code Overview

The main components of the application include:

- Clock Component: This component handles the display of the current time.
- Time Component: This componenr manages the interval for updating the time.

### Key Lifecycle Methods

- componentDidMount: Sets an interval to update the clock every second when the component is mounted.
- componentWillUnmount: Clears the interval to prevent memory leaks when the component is removed.

## Contributing
Contributions are welcome! Please submit issues or pull requests for any enhancements or bug fixes.

## License
This project is licensed under the [MIT License](LICENSE).
