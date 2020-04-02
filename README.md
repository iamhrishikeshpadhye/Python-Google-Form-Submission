# Python-Google-Form-Submission
A Python script to fill and submit Google forms.

## How to use?
Install the ```requests``` module of Python using ```pip```<br>
```
pip install reuests
```
Clone the repository
```
git clone https://github.com/iamhrishikeshpadhye/Python-Google-Form-Submission.git
```
Open ```AutoGForm.py``` in your favourite editor.<br>
![Code in editor](https://github.com/iamhrishikeshpadhye/Python-Google-Form-Submission/blob/master/Screenshots/AutoGForm-Code.png)
<br>
Copy the link of your Google form and paste it in the quotes of ```url``` variable.<br>
<br>
Replace ```/viewform``` by ```/formResponse``` in the url variable.<br>
<br>
To fill the data for the Google form, we need to identify the ```entry.<id>``` for the fields of the form.<br>
You can find the ```entry.<id>``` from your browser by using 'Inspect Element' feature on the fields of the form.<br>
![Inspect Element](https://github.com/iamhrishikeshpadhye/Python-Google-Form-Submission/blob/master/Screenshots/AutoGForm-get_entry_id.jpg)
<br>
Copy the ```entry.<id>``` from the 'Inspect Element' window for every feild to the ```submission``` dictionary in the code and fill your data accordingly in the quotes.
<br>
Run the code in the terminal<br>
```
python AutoGForm.py
```
You will see ```Success!``` or ```An error has occurred.``` as per the response of the POST request made.


### Authors

 **Hrishikesh Padhye**

* Twitter: [@Hrishi_says_so](https://twitter.com/Hrishi_says_so)
* Github: [iamhrishikeshpadhye](https://github.com/iamhrishikeshpadhye)

#### Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues](https://github.com/iamhrishikeshpadhye/Python-Google-Form-Submission/issues) page.

#### Support this project :)

Give a ⭐️ if you like this!
