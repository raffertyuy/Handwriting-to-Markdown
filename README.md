# Handwriting-to-Markdown
This is an Azure Logic Apps that checks a OneDrive folder for new files and converts it to a Markdown `.md` text file using Azure Cognitive Service - Computer Vision API.

You can read more about this logic app in this [blog post](/raztype/handwriting-to-second-brain/).

## Quick Deploy to Azure
![Logic App Screenshot 1](/img/logicapp-part1.png)
![Logic App Screenshot 2](/img/logicapp-part2.png)

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fraffertyuy%2FHandwriting-to-Markdown%2Fmaster%2FHandwriting-to-Markdown-LogicApp%2Fazuredeploy.json)

## Potential Enhancements
This logic app was created quickly and for personal use. For corporate/production use, here are a few enhancement suggestions:
1. Change to Onedrive for Business
2. Store keys in Azure Key Vault
3. Logging
4. Error Handling
5. Append scan image URL in the converted .md file `![caption](image url)`