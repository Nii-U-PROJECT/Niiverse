## Niiverse
Niiverse. A Miiverse clone based off [Indigo](https://github.com/PF2M/Indigo "Indigo"), made by the Nii U Team. It looks more like Miiverse's original design.

## Installation
1. Install the latest version of Go from https://golang.org or from the official GOLANG repository.
2. Download the .ZIP file or clone the repository like any other project.
3. Install all the dependencies with go get ./....
4. Set up a MySQL server and import structure.sql.
5. Modify the config.json file to your liking.
6. Optional: If you want to install GeoIP (necessary for user timezones to be correct and getting user regions), download a GeoLite database from MaxMind, unzip the file and rename it geoip.mmdb and put in the same folder as main.go.
7. Build the server with go build and then run the new program that is created, or use go run *.go (Linux/MacOS only).
8. Make an account, give yourself admin through the MySQL CLI (UPDATE users SET level = 9 WHERE id = 1, for example) or your favorite database management interface (e.g. PHPMyAdmin), and start making some communities!

## About
Niiverse is a Miiverse Clone, based off Indigo like we said earlier. We are a group of teens making Homebrews and explorating Wii U/3DS System.
