## Solutions for AI-Hackathon-2023 Final Contest Held by Irancell. <br>
My teammate was [Sina Asghari](https://github.com/sinaaasghari) and our team ranked **No.1** in the contest score and **No.5** overall. <br>
Due to the Contest Code of Conduct, we **cannot** share datasets publicly, but I will try to explain the schema. ( Sorry in advance  ). <br>
I hope you Enjoy :). <br>
The contest contained 2 questions that were judged by an automated system, here I will explain these two.
### Problem No.1:
After unzipping the dataset, you will see folders whose names represent a date.<br>
Each of these folders contains folders with the names of news sources that were observed on that date and their news was collected.<br>
Inside each of the folders related to news sources, the HTML files collected from that news source are placed.
<pre>
data
├── 2023-08-05
│   ├── 7sobh
│   │   ├── 0.html
│   │   └── 1.html
│   └── farsnews
│       ├── 0.html
│       └── 1.html
└── 2023-08-04
    ├── varzesh3
    │   ├── 0.html
    │   └── 1.html
    └── snn
        ├── 0.html
        └── 1.html
</pre>
Queries : 
- How many unique news sources are there in the dataset?
- Which news source has the most HTML files in the entire dataset?
- Consider all HTML files related to varzesh3. Get the number of repetitions of the words `کشتی`, `والیبال`, and `فوتبال` in all p​​ tags, respectively.
- Find the most repeated word in h2 tag among all news collected on 2023-08-01. (You could use the stopwords array placed in the initial file)
