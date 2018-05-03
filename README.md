<h1 align="center"> Survey Winner Drawing</h1>
This program picks the winners from a csv file with emails on each line

## Running the Program
### Formatting the CSV file
The CSV file must meet the following requirements:
1. 1 column of emails
2. No empty rows

There is no check if the entry is an email so the participants can enter their username as well.

### Compiling the Program
To compile the program and get it ready to run enter the following command in the terminal:
```bash
javac *.java
```

### Running the Program
To run the program enter the following command:
```bash
java QualtricsLottery <number of winners> <path to csv file>
```
The first argument is the number of winners that will be picked. The second argument is the path to the CSV file. If the file is in the same folder it will just be the name of the file.

### Problems?
Create a pull request or create an issue. Or contact ITC@uwec.edu for support.
