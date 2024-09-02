# 📄🤖 PDF Question Answering with Huggingface on AWS SageMaker 🚀

## Introduction
This project leverages Huggingface's pre-built Question Answering (QA) model, deployed on AWS SageMaker, to provide accurate answers to questions extracted from PDF documents. By combining advanced NLP with scalable cloud infrastructure, users can interact with PDFs seamlessly.

![image](https://github.com/user-attachments/assets/09aa033f-2898-4be7-aaec-471379c26923)
## 🛠️ Skills/Concepts Developed
- Huggingface Transformers
- AWS SageMaker Deployment
- PDF Text Extraction (PyPDF2)
- Boto3 for AWS Integration

## ❓ Problem Statement
How can we build an intelligent system that allows users to ask questions directly from a PDF document and receive accurate answers in real-time?

## 🌍 Impact of Your Work
- **Enhanced Accessibility**: Facilitates quick information retrieval from complex documents.
- **Scalable Solution**: Deployed on AWS SageMaker, ensuring reliability and scalability.
- **Time-Saving**: Reduces manual document search efforts, providing instant answers.

## 🧠 Modeling
### Steps
1. **PDF Text Extraction**: Utilize `PyPDF2` to parse and extract text from PDF documents.
2. **Model Selection**: Deploy the `distilbert-base-uncased-distilled-squad` QA model from Huggingface.
3. **AWS SageMaker Deployment**: Use SageMaker to create an endpoint for real-time inference.
4. **Inference**: Input questions, receive answers based on the extracted text.

## 🏁 Conclusion
This project showcases the integration of state-of-the-art NLP with cloud computing, providing an efficient solution for document-based question answering.

## 💡 Recommendations
- **Expand to Other Document Formats**: Extend functionality to handle DOCX, TXT, etc.
- **Model Optimization**: Fine-tune the QA model for specific use cases to improve accuracy.
- **Batch Processing**: Implement batch processing for large-scale document analysis.

## 🙌 Credits
- Huggingface for the QA model.
- AWS for scalable deployment.
- `PyPDF2` for PDF parsing.

## 🖋️ About the Author
[Prakash.P](https://www.datascienceportfol.io/prakashScientist) is a [Data Scientist] with expertise in [Modeling]. Feel free to reach out for any questions or collaborations at [prakash2822001@gmail.com].

