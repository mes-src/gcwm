# grahamcapitalwealth.io
**If, the above notebook fails to load you can copy the url of the notebook into the jupyter notebook viewer url.
The URL of the notebook is: https://github.com/mes-src/gcwm/blob/master/grahamcapitalwealthio.ipynb   <br/>
The link to the jupyter notebook viewer is: https://nbviewer.jupyter.org/   <br/>
<br/>
<br/>
_______About the Project - _______
this is a web application writen in Python, using the Django web framework, and deployed on aws Elastic Beanstalk. <br/><br/> this project uses an SFTP server to recieve data files that are pushed to it by our brokerage firm (Fidelity). These files are parsed and then populated into a PostgreSQL database using aws RDS. <br/><br/> Highcharts.js as well as the django RestFULL API are utilized to provide insightful graphics and interfaces enabling users to interact with the backend database. <br/><br/> datafiles are automaticaly parsed, populated, and stored on aws S3 using Cron task scheduelling each morning. This enables compliance report generating and client portfolio analytics to be built on the backend and prepared for servicing to users upon request. <br/><br/> More frequent iterations of cronjobs also enables a live datafeed of security bid, ask spreads to feed into a Special Purpose Acquisition Company (SPAC) arbitrage model, therefore identifying trade opportunities in real time based upon expected Yield to Maturities. <br/><br/> SSL & OAuth are implemented to handle authentication outside of the default django-admin system.



@ 2020
