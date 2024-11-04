# Bulid Senitment_Analysis_Bot By Using OpenAI API

This guide will walk you through the steps to create a sentiment analysis bot using OpenAI's API.

## Steps to Follow

1. **Create an OpenAI Account**  
   If you don’t already have an account, sign up [here](https://platform.openai.com/). If you already have an account, simply log in.

2. **Deposit Funds to Access the API**  
   To use OpenAI's API, you’ll need to deposit $5 (approximately 1600 PKR). You can use Mezan Bank or Nayapay for the transaction.  
   - Navigate to: `OpenAI -> Billing -> Add Your Payment Method`
   - Deposit $5 (1600 pkr from Mezan_Bank Master Card) 
   - Adjust your usage limits if desired (tutorial available here).

3. **Create an API Key**  
   Generate an API key, then copy and save it into a `.txt` file for later use.

4. **Download the Sentiment Analysis File**  
   Get the "sentiment_analysis" file from this repository, and open it in Jupyter Notebook.

5. **Set Up the API Key**  
   In the file, paste your API key into the variable:  
   ```python
   openai.api_key = "your_api_key_here"
