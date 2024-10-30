<a id="readme-top"></a>
<div align="center">
  <a href="https://github.com/dfoulkes-au/arf-rhd-calculator"><img src="./favicon.ico" alt="ARF Logo" width="80" height="80"></a>
  <h2>Calculator for Acute Rheumatic Fever (Experimental) - Deployment Package</h2>
</div>


## Overview

This project is a deployment package including html/js/css etc for a browser-based single page application providing a user friendly implementation of the 2020 Australian criteria for Acute Rheumatic Fever diagnosis - based on Revised Jones Criteria for the Australian context.

**NOTE: This is experimental software and is not approved for diagnostic purposes.**

[Here](https://arf-calculator.nardhc.org/) is an example of the ARF Calculator.

To deploy this package simply clone the repo and copy the contents to a web server folder.

The code for this project describes a single page application that can be built using NodeJS, the Vue 3 framework, and Vuetify UI Library.   If you wish to access the code to modify or contribute to the project,  you can find it [here](https://github.com/dfoulkes-au/arf-rhd-calculator).

If you like this, don't forget to give the project a star! Thanks!

## Background

Acute rheumatic fever (ARF) results from the body’s autoimmune response following an infection with Group A Streptococcus bacterium (Streptococcus pyogenes). Rheumatic heart disease (RHD) refers to the long-term cardiac damage caused by either a single severe episode or multiple recurrent episodes of ARF.  The development of ARF occurs approximately two weeks after S. pyogenes infection . The clinical manifestations and symptoms of ARF can be severe and are described in the Revised Jones Criteria.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Deployment

In order to deploy the ARF Calculator,  first Clone this repository by executing:

```sh
git clone https://github.com/dfoulkes-au/arf-rhd-calculator-dist.git
```

To deploy the package on the internet, you will need to have access to a web server and have permissions to copy files to the a folder that is served by the web server.
In this case,  simply copy all files and folders from the folder you have cloned to a specified folder on your web server.  You should then be able to access the IG in your browser.

If you want to test the ARF Calculator on a local computer,  then install Python.   Then change to the folder on your computer that contains the cloned content.
Run the following command:

```sh
python -m SimpleHTTPServer
```

Then in your browser go to http://localhost:8000/index.html

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## About the Project

### How to Contribute

Issues and or pull requests for this deployment project will not be monitored.  

The content of this project is derived by an automated compilation process from the [source code project](https://github.com/dfoulkes-au/arf-rhd-calculator).

So if you have contributions or suggestions please go to the source project, and follow the "How to Contribute" instructions there.

### License

Distributed under the MIT License. See [LICENSE.md][license-url] for more information.

### Acknowledgments and Links

- [2020 Updated Australian criteria for ARF diagnosis](https://www.rhdaustralia.org.au/system/files/fileuploads/a3_2020_updated_criteria_for_arf_diagnosis.pdf)

### Contacts

- [Northern Australian Regional Digital Health Collaborative][linkedin-nardhc-url]
- [Daniel Foulkes][linkedin-df-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

[linkedin-df-url]: https://www.linkedin.com/in/daniel-foulkes/
[linkedin-nardhc-url]: https://www.linkedin.com/company/101721851
[license-url]: https://github.com/dfoulkes-au/arf-rhd-calculator/blob/main/LICENSE.md
