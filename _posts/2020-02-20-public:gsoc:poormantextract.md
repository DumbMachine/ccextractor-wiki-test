
# Poor Man's Textract

**Introduction**
Amazon Textract a (paid) service that “automatically extracts text and data from scanned documents. Amazon Textract goes beyond simple optical character recognition (OCR) to also identify the contents of fields in forms and information stored in tables.”. We want to build a free alternative that provides an output of similar quality. 

**Your job**
First, you'll need to find lots of documents to process around the internet. We will provide you some, but you need to build your own corpus. A few ideas:

- Tax documents.\\
- Multiple-choice exams.\\
- Immigration forms.\\
- Resumes.\\
- Contracts.\\
- Blueprints.\\
- Order forms.\\
- Invoices.\\

... and many more.

Then create a system that is able to identify the parts of all those models, write some output (for example, a JSON file) that contains the coordinates of each of the parts, writes each part to a separate file, and OCRs whatever information can be OCR'ed and writes it to a database (which can be as simple as document storage or a full-fledged SQL instance of your preferred flavor).

We strongly recommend you play a bit with Amazon's Textract (for online tests it's free) to get an idea of what to expect.

To get you started a bit you may take a look at what the GCI students did during last Christmas break (which only works for one specific use case, but it's a reasonable proof of concept):

[Musab Kılıç's exam analyzer](https://github.com/musabkilic/ExamAnalyzer)\\
[RobOHt's exam analyzer](https://https://github.com/RobOHt/AutomataQP-Decomposer)\\
[knightron0's exam analyzer](https://github.com/knightron0/exam-analyzer)

**Qualification tasks**\\
Take a look at [this page](https://ccextractor.org/public/gsoc/takehome).

