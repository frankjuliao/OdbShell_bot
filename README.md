<h1> OdbShell_bot </h1>

<h2>About: </h2>

**OdbShell_bot** Connect to device ODB2 car, and collect data, example: speedODB, speedGPS, latitude and longitude, update data to database in create file json.
Data Update format json to mysql.

<h2> Requisite:</h2>
<table>
<thead>
<tr>
<th>Package</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<tr>
<td>jq (1.5 or +) (<a href="https://stedolan.github.io/jq/download" rel="nofollow">Download</a>)</td>
<td>JSON command processor</td>
</tr>
<tr>
<td>curl</td>
<td>Command line tool to transfer data using various protocols.</td>
</tr>
<td>Token id Telegram (<a href="https://core.telegram.org/bots#3-how-do-i-create-a-bot" rel="nofollow">Download</a>)</td>
<td>Bot required.</td>
</tr>
</tbody>
</table>

<h3>How to use: </h3>

* Create database in mysql or import

```
CREATE TABLE odb_shell
(
 id INT AUTO_INCREMENT PRIMARY KEY
 , dados JSON
) ENGINE = InnoDB;

```

* Change data in the connect.conf file

* Set script permission to execution # chmod +x

* Run OdbShell_bot
example: ./OdbShell_bot OR bash OdbShell_bot


<h2> Contact: </h2>

* E-mail: frank.juliao@hotmail.com

<h2> Developer:</h2>

* Franklinaldo Silva 
