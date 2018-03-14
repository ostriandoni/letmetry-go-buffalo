# Simple Web App Using Buffalo

[![forthebadge](https://forthebadge.com/images/badges/made-with-go.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/60-percent-of-the-time-works-every-time.svg)](https://forthebadge.com)

## Create Your Databases

Edit the `database.yml` file to use the correct usernames, passwords, hosts, etc. that are appropriate for your environment. To create the databases in that file, run the following command:

	$ buffalo db create -a

## Starting the Application

To watch your application and automatically rebuild the Go binary and any assets, run the following command:

	$ buffalo dev

Point your browser to [http://127.0.0.1:3000](http://127.0.0.1:3000), and now have your Buffalo application up and running.

[Powered by Buffalo](http://gobuffalo.io)
