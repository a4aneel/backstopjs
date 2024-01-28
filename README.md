# BackstopJS Visual Regression Testing Project

This project uses BackstopJS for visual regression testing. BackstopJS is a tool for automating visual regression testing of your web applications.

## Setup

1. Clone this repository:

   ```bash
   git clone https://github.com/a4aneel/backstopjs.git

2. install dependencies
   
   ```bash
   npm install

3. Configuration
   
The BackstopJS configuration can be found in the backstop.json file. Update the scenarios, viewports, and other settings based on your project requirements.

5. Running Tests
To run visual regression tests, use the following command:

```bash
npm run backstop:test
This will generate and compare screenshots based on your configuration.

Generating Reference Screenshots
If you want to update the reference screenshots, use:

bash
Copy code
npm run backstop:reference

