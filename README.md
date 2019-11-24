# Internally Displaced Persons

## 1. Description
An internally displaced person (IDP) is someone who is forced to flee his or her home but who remains within his or her country's borders. This **Visualization project** is focused on the IDPs associated to natural events, such as storms, wildfires, earthquakes, storms, landslides, and some more. 

The visualizations have been done keeping in mind the [Data-Ink Ratio](https://infovis-wiki.net/wiki/Data-Ink_Ratio) . Using Plotly and Plotly Express.

### Questions
- Is the number of natural disasters increasing with the years? Is flood the major cause for IDPs?
- How is the number of natural disasters moving with the earth's surface temperature?
- Are the natural disasters being more catastrophic (causing more IDPs)?

## 2. Files
- data_preparation: loads and processes all the data that will be needed for the visualization part.Exports pickle file with merged dfs
- Plotting: notebook used to visualize and answer to the presented questions. The following visualizations are produced:
  1. Main natural causes for IDPs in the last 10 years
  2. Monthly distribution of IDPs and events in the last 10 years
  3. Main natural cause for IDPs by year from 2008-2018
  4. Number of natural disasters by continent
  5. Number of natural events vs anomalies in temperature
  6. Map representation of the natural events and their impact in the last 10 years
  7. Exploring a country
  8. Top 10 countries with the highest number of natural events
  9. Top 10 countries with the highest number of IDPs
- Input: Folder containing  the csv used as input for the analysis.
- Output: Folder containing the pickle file exported from the data_preparation notebook

## 3. Data Sources

- For the IDPs: https://data.humdata.org/dataset/idmc-internally-displaced-persons-idps-new-displacement-associated-with-disasters

- Average temperature 1991-2016: https://climate.nasa.gov/vital-signs/global-temperature/

## 4. Environment dependancies:
- appnope==0.1.0
- asn1crypto==1.2.0
- attrs==19.2.0
- backcall==0.1.0
- beautifulsoup4==4.8.1
- bleach==3.1.0
- certifi==2019.9.11
- cffi==1.13.0
- chardet==3.0.4
- Click==7.0
- colorama==0.4.1
- coverage==4.5.4
- cryptography==2.8
- cycler==0.10.0
- dash==1.4.1
- dash-core-components==1.3.1
- dash-html-components==1.0.1
- dash-renderer==1.1.2
- dash-table==4.4.1
- decorator==4.4.0
- defusedxml==0.6.0
- entrypoints==0.3
- Flask==1.1.1
- Flask-Compress==1.4.0
- future==0.18.2
- geographiclib==1.50
- geopy==1.20.0
- idna==2.8
- importlib-metadata==0.23
- ipykernel==5.1.2
- ipython==7.8.0
- ipython-genutils==0.2.0
- itsdangerous==1.1.0
- jedi==0.15.1
- Jinja2==2.10.3
- joblib==0.13.2
- jsonschema==3.0.2
- jupyter-client==5.3.3
- jupyter-core==4.5.0
- kiwisolver==1.1.0
- langdetect==1.0.7
- LatLon==1.0.2
- MarkupSafe==1.1.1
- matplotlib==3.1.1
- mistune==0.8.4
- mkl-fft==1.0.14
- mkl-random==1.1.0
- mkl-service==2.3.0
- more-itertools==7.2.0
- nbconvert==5.6.0
- nbformat==4.4.0
- notebook==6.0.1
- numpy==1.17.2
- packaging==19.2
- pandas==0.25.1
- pandocfilters==1.4.2
- parso==0.5.1
- patsy==0.5.1
- pexpect==4.7.0
- pickleshare==0.7.5
- plotly==4.3.0
- plotly-express==0.4.1
- pluggy==0.13.0
- pprintpp==0.4.0
- prometheus-client==0.7.1
- prompt-toolkit==2.0.10
- ptyprocess==0.6.0
- py==1.8.0
- pycountry==19.8.18
- pycountry-convert==0.7.2
- pycparser==2.19
- Pygments==2.4.2
- PyMySQL==0.9.3
- pyOpenSSL==19.0.0
- pyparsing==2.4.2
- pyproj==2.4.1
- pyrsistent==0.15.4
- PySocks==1.7.1
- pytest==5.3.0
- pytest-cov==2.8.1
- pytest-mock==1.12.0
- python-dateutil==2.8.0
- pytz==2019.3
- PyYAML==5.1.2
- pyzmq==18.1.0
- repoze.lru==0.7
- requests==2.22.0
- retrying==1.3.3
- scikit-learn==0.21.3
- scipy==1.3.1
- seaborn==0.9.0
- Send2Trash==1.5.0
- six==1.12.0
- soupsieve==1.9.3
- SQLAlchemy==1.3.10
- statsmodels==0.10.1
- terminado==0.8.2
- testpath==0.4.2
- tornado==6.0.3
- traitlets==4.3.3
- urllib3==1.24.2
- wcwidth==0.1.7
- webencodings==0.5.1
- Werkzeug==0.16.0
- xlrd==1.2.0
- zipp==0.6.0


