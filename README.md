# google-trends


**Tools used:**
* `ioutil` Reading body of response from url request
* `http` Making data requests
* `encoding/xml` Unmarshalling of xml data

I create a an outline for our data with structs, and then we pass a reference to the main "RSS" struct to xml.Unmarshal, which will fill that reference with data from the XML document. We then iterate through that object, printing out the data of interest. 

<img width="910" alt="Screenshot 2023-11-21 at 3 46 36 PM" src="https://github.com/mfkimbell/google-trends/assets/107063397/c558ca96-df65-46b1-afcc-037c68215173">
