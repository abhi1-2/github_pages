# <center><span style="text-decoration:underline;">Docparser - OCR & Information Extraction 
 <a style="position:relative; right: -80%;" href="mailto:avishek.sarkar@box8.in">by <b>Avishek Sarkar </b></a>

</span>
</center>

## **<span style="text-decoration:underline;">CONTENT</span>**



1.  <a href='#intro'>Introduction</a>
2.  <a href="#landscape">The OCR Landscape</a>
3.  <a href="#failures">Where the current OCR APIs fail</a>
4.  <a href="#ocr_need"> Should I even consider using OCR then?</a>
5.  <a href="#good_ocr"> What defines a good OCR product?</a>
5.  <a href="#docparser"> OCR & Docparser </a>



## 1. <a name="intro" style="text-decoration:underline;"> Introduction</a>

Simply defined, OCR is a set of computer vision tasks that convert scanned documents and images into machine readable text. It takes images of documents, invoices and receipts, finds text in it and converts it into a format that machines can better process. You want to read information off of ID cards or read numbers on a bank cheque, OCR is what will drive your software.

 You might need to read the different characters from a cheque, extract the account number, amount, currency, date etc. But how do you know which character corresponds to which field? 

   <center><img src = "https://nanonets.com/blog/content/images/2019/08/clearcheck21_micr_reader-568141.jpg " style="width:70%"></center>
   

## 2. **<a name="landscape" style="text-decoration:underline;"> The OCR landscape</a>**

OCR is perceived to be a solved problem by many, but in reality, the products available to us as open-source tools or provided by technological giants are far from perfect - too rigid, often inaccurate and fail in the real world.

![alt_text](https://nanonets.com/blog/content/images/2019/08/OCR_illustration-02--3-.jpg "image_tooltip")

The APIs provided by many are limited to solving a very limited set of use cases and are averse to customizations. More often than not, a business planning to use OCR technology needs an in-house team to build on the OCR API available to them to actually apply it to their use case. The OCR technology available in the market today is mostly a partial solution to the problem.



## 3. **<a name="failures" style="text-decoration:underline;">Where the current OCR APIs fail</a>**
1. Require a considerable amount of post-processing

2. Work well only in specific constraints 
3. Tilted text in images
4. Handwritten text, cursive fonts, font sizes
5. Noisy/blurry images





## 4. **<a name="ocr_need" style="text-decoration:underline;">Should I even consider using OCR then?</a>**
Short answer is <b>Yes</b>.

Anywhere there is a lot of paperwork or manual effort involved, OCR technology can enable image and text based process automation. Being able to digitize information in an accurate way can help business processes become smoother, easier and a lot more reliable along with reducing the manpower required to execute these processes. For big organizations who have to deal with a lot of forms, invoices, receipts, etc, being able to digitize all the information, storing and structuring the data, making it searchable and editable is a step closer to a paper-free world.

Think about the following use cases - 
1. <span style="text-decoration:underline;">Legal documents</span> -
    Dealing with different forms of documents - affidavits, judgments, filings, etc. digitizing, databasing and making them searchable.

 2. <span style="text-decoration:underline;">Table extraction</span> - 
    Automatically detect tables in a document, get text in each cell, column headings for research, data entry, data collection, etc.

  3.  <span style="text-decoration:underline;">Banking</span> - analyzing cheques, reading and updating passbooks, ensuring KYC compliance, analyzing applications for loans, accounts and other services.

  4. <span style="text-decoration:underline;">Healthcare</span> - have patients medical records, history of illnesses, diagnoses, medication, etc digitized and made searchable for the convenience of doctors.

5. <span style="text-decoration:underline;">Invoices</span> - automating reading bills, invoices and receipts, extracting products, prices, date-time data, company/service name for retail and logistics industry.

## <a name="good_ocr" style="text-decoration:underline;">What defines a good OCR product?</a>

 1. How it deals with the images coming in 
 2. How it performs in real-world problems
 3. How it uses the machine-readable text


## <a name="docparser" style="text-decoration:underline;">Docparser & OCR</a>
Docparser was built to solve these kind of problems. We have been able to productize a pipeline for OCR by working with it as not just character recognition but getting structured usable information.


 <center><img src="https://nanonets.com/blog/content/images/2019/08/OCR_illustration-2.gif" height=50% width=70%></center>


 **Benefits of Docparser**:
1. Docparser saves precious time by providing structured usable information which can be used for autofilling forms etc.
2. Prevents error due to User entry.
3. Increases overall productivity.
4. Compatibility with local languages. 

Docparser Pipline

<img src="http://drive.google.com/uc?export=view&id=1Qds2KUbNeOGHiM_AHBobnsjuj-d7IHN0">

