Doc2Pdf
Browser-Based Document to PDF Converter

A lightweight, secure, and client-side web application that converts various document formats and images into PDF files directly in the browser.

🚀 Features

Multi-Format Support: Convert .docx, .txt, .rtf, .html, and common image formats (.jpg, .jpeg, .png) to PDF.

Privacy First: All processing happens locally on your machine. No files are ever uploaded to a server.

Optimized File Size: High-fidelity text rendering for documents and compressed JPEG embedding for images to ensure small, shareable output files.

Drag & Drop: Intuitive user interface with drag-and-drop file support.

Live Preview: View your document content before finalizing the conversion.

🛠️ Technology Stack

This project is built using vanilla JavaScript and the following libraries:

Mammoth.js: For high-quality .docx to HTML conversion.

jsPDF: The core library for generating PDF documents.

html2canvas: Used for capturing visual layouts (primarily for image-based conversions).

📂 Installation & Usage

Since this is a client-side application, no server-side setup or npm install is required.

Clone the repository:

git clone [https://github.com/your-username/document-to-pdf-converter.git](https://github.com/your-username/document-to-pdf-converter.git)


Open Word2pdf.html in any modern web browser.

Drag your file into the drop zone or click to select a file.

Click Convert to PDF.

Once processing is complete, click Download PDF.

⚙️ How it Works

The converter uses a hybrid logic system to maintain quality while keeping file sizes low:

Text Documents: Extracts text/HTML and renders it directly as vector text in the PDF.

Images: Automatically scales and compresses images to 75% JPEG quality to prevent massive file sizes while maintaining readability.

🔒 Security

This application is completely "Serverless." It utilizes the File API and local memory. Your sensitive data never leaves your browser, making it safer than many online conversion tools.

📄 License

This project is open-source and available under the MIT License.
