
# IBM-ticker-API

This application connects to Alpha-Vantage and retrieves the latest IBM stock movements of the day. It shows the prices with 5min intervals.
The application then turns the data into a dataframe which the user can further manipulate. 
The program can generate graphs of the time series and the code can be altered to retrieve information for other major companies. 

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)


---

## Table of Contents

1. [About the Project](#about-the-project)
2. [Getting Started](#getting-started)
3. [Usage](#usage)
4. [Features](#features)
5. [Contributing](#contributing)
6. [License](#license)
7. [Acknowledgments](#acknowledgments)

---

## About the Project

This is a simple application, which allows the user to request data from Alpha-vantage. Due to the low number of requests available for free (25)
This app has been developed in order to make dataframes for your most important stocks wich need 5-min accuracy in prices. 

### Screenshots


## Getting Started

To get started with this application. Follow the step-by step guide below. 

### Prerequisites

List tools and dependencies needed:
- Python 3.10+
Libraries used:

- requests
- os
- dotenv
- -pandas

Other requirements:
-pip install
-pipenv
-Internet browser (chrome)



### Installation

To install, follow the steps

```bash
# Clone the repo
git clone https://github.com/yourusername/repo.git
# Navigate to the project directory
# Install dependencies using pipenv
```

## Setting up your preferences:
1.Use your web-browser to get to https://www.ica.se/butiker/
2.Search for your local store and go to the page.
3.Copy the url and save it somewhere you can retrieve it from. 
4.Open the chat_gpt_app.ipynb file and change 

![Screenshot of the project](ica3.png)



## Features

Highlight key features:

- 📊 Interactive visualizations
- ⚡ Real-time updates
- 🔐 Secure authentication
- 🌍 Localization support

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/new-feature`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature/new-feature`).
5. Open a pull request.

Refer to [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.

---

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Acknowledgments

If there are any
