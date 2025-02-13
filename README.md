# Google_gemini2.0

[link to article](https://pub.towardsai.net/extract-any-document-with-gemini-2-0-document-intelligence-with-extractthinker-4eda6eed99e5)

This article will talk about Google Gemini 2.0 and how it helps with intelligent document processing (IDP)

## Intelligent Document Processing (IDP)

IDP turns unstructed data (ex. invoices, drivers license, & reports) into structured information. LLMs can process images & PDFs but the LLM does not give perfect results.

Intelligent document processing combines 4 things:

1. OCR (object character recognition). Some OCR tools are Google document AI, Tesseract, PyPDF)
2. Classification -to identify the document type (invoice, contract license, etc)
3. Splitting to handle large files and break them into sections
4. Extraction to map information into structured Pydantic models -getting necessary information like the invoice number, date, getting chart data, etc

## ExtractThinker library

The ExtractThinker library combines all of the 4 steps listed above & lets you integrate them when using Google gemini 2.0

The ExtractThinker library does the 4 steps mentioned eariler:

1. Load documents via a OCR tool
2. Classify documents
3. Split the documents
4. Extract documents information

## linux setup

create environment -> then create virtual environment 

## Connecting to Visual Studio Code (connecting & finding the IP Address)
