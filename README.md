# Console Finance Calculator


## Description

This project is for a console-based financial analysis application that is written in Javascript. The application uses a data set in the form "'MMM-YYYY', PROFIT(num)" to calculate total months analysed, net total profit over that period, average change in profits over that period, and the greatest increase and decrease in profits shown in the data month-to-month.

The data provided with the application is not exhaustive, and can be subject to an increase or decrease in the number of data points present whilst the application's functionality is maintained. This would require elements to be added to the 'finances' array in Javascript. 



## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)


## Installation

N/A 


## Usage

Press CTRL + SHFT + I (Windows) or CMD + SHFT + I (Mac OS) to open the Chrome DevTools window and change to the 'Console' tab to view the application. 

Call the 'finances' variable by inputting 'finances' into the console. Press 'Enter' and engage the drop-down to the left of the array to view the data analysed in the application. 

To add monthly data to the data set, enter `finances.push(["MMM YYYY", 00000]);` into the console in the displayed format.

To remove the last set of data, enter `finances.pop()` into the console.

To remove the first set of data, enter `finances.shift()` into the console.


## Credits

N/A 


## License

Please refer to the LICENSE in the repo. 

---