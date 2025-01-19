# NICT Solar Spectra Scraper

## Introduction

This repository contains a web scraper designed to extract solar radio dynamic spectra data from the National Institute of Information and Communications Technology (NICT) database. The scraper collects data from:

- **HiRAS**: Solar radio dynamic spectra from 1996 to 2016.
- **YAMAGAWA**: Solar radio dynamic spectra from 2016 to present.

The data can be used for research and analysis of solar phenomena.

For more details about the NICT solar observation database, visit their website: [NICT Solar Observation Database](https://solarobs.nict.go.jp/).

## Features

- Extracts solar radio dynamic spectra data.
- Supports data retrieval from HiRAS and YAMAGAWA datasets.
- Easy to use and customize.
- A custom mini parser was developed to solve the captcha on the website bypassing the human effort needed and automating it entirely.

## Installation

1. Clone the repository:
   ```bash
   https://github.com/Girik-Khullar/NICT-Solar-Observation-Scraper.git
   ```

2. Navigate to the project directory
   ```bash
   cd NICT-Solar-Observation-Scraper
   ```
3. Install the required dependencies
   ```bash
   pip install -r requirements.txt
   ```
   
## Usage

As of now, the scrapper is present in a jupyter notebook. To use, just modify the configuration variables as per your choice and then run the whole notebook.
A python script will be uploaded later.

[Watch the video](https://github.com/Girik-Khullar/NICT-Solar-Observation-Scraper/blob/main/Scrapper%20Demo.mp4) The video is big enough which is why GitHub is unable to render it. Kindly Download it to watch.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Citation

If you use this web scraper in your research or projects, please cite it as follows:

```
@software{nict_solar_spectra_scraper,
  author = {Girik Khullar},
  title = {NICT Solar Spectra Scraper},
  version = {1.0},
  url = {https://github.com/Girik-Khullar/NICT-Solar-Observation-Scraper},
  year = {2024}
}
```

## Contributing

Feel free to open issues or submit pull requests. Contributions are welcome!
