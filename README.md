# Awesome-Document-Intelligence-PDF-Parsing-OCR

markdown
# Top Document Intelligence & PDF Parsing OCR Ecosystem

**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  
*Focused on AI Document Parsing, Layout-Aware PDF-to-Markdown Extraction, Optical Character Recognition (OCR), Table/Form Extraction & RAG Ingestion Pipelines*  
**Last updated: November 2026**

This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Document Intelligence & PDF Parsing OCR**. These tools parse, OCR, extract tables, reconstruct reading order, and convert complex PDFs, scanned invoices, research papers, and office documents into clean Markdown, JSON, and HTML for LLM RAG pipelines, enterprise IDP (Intelligent Document Processing), and automated data extraction.

**Examples** include Unstructured.io, LlamaParse, AWS Textract, Google Document AI, Azure AI Document Intelligence, Rossum, ABBYY FlexiCapture, Klippa, Docsumo, Nanonets, and firecrawl/pdf-inspector (the category leaders and popular runtimes). 

**Open-source emphasis**: This section is heavily expanded with every major active project for layout-aware PDF-to-Markdown & VLM document parsing (`Docling`, `Marker`, `MinerU`, `firecrawl/pdf-inspector`, `Unstructured OSS`, `olmOCR`), high-speed PDF text/table extraction (`PyMuPDF`, `PDFPlumber`, `pdfplumber/Camelot`), and multilingual OCR engines (`PaddleOCR`, `Surya`, `Tesseract`, `EasyOCR`) — ideal for AI/RAG engineers, data engineers, document automation teams, and archival researchers.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Support & Share](#support--share)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[LlamaParse (LlamaIndex Cloud)](https://llamaindex.ai)**  
  GenAI-native cloud document parsing platform converting complex PDFs, tables, charts, and embedded images into structured Markdown and JSON optimized for LLM RAG pipelines.

- **[Unstructured.io (Unstructured Platform)](https://unstructured.io)**  
  Enterprise unstructured data preprocessing and ETL platform transforming PDFs, Word docs, HTML, and emails into clean, chunked JSON elements for vector databases.

- **[Azure AI Document Intelligence (Microsoft)](https://microsoft.com)**  
  Managed cloud OCR and document extraction service offering prebuilt models for invoices, receipts, IDs, tax forms, layout analysis, and custom neural extraction models.

- **[AWS Textract](https://amazon.com)**  
  Managed AWS machine-learning OCR service automatically extracting printed text, handwriting, key-value form pairs, and structured tables from scanned documents.

- **[Google Cloud Document AI](https://google.com)**  
  Enterprise document understanding platform combining high-accuracy OCR, layout parser for RAG chunking, and specialized processors for procurement, lending, and identity documents.

- **[Rossum](https://rossum.ai)**  
  Cloud AI-first Intelligent Document Processing (IDP) platform specialized in transactional business documents (invoices, purchase orders, bills of lading) with human-in-the-loop validation.

- **[ABBYY Vantage & FlexiCapture Cloud](https://abbyy.com)**  
  Industry-veteran enterprise OCR and Intelligent Document Processing suite delivering high-precision multi-language recognition, document classification, and ERP connectors.

- **[Klippa DocHorizon](https://klippa.com)**  
  Cloud Intelligent Document Processing and OCR API platform offering automated data extraction, fraud detection, and anonymization for financial, logistics, and identity documents.

- **[Docsumo](https://docsumo.com)**  
  Document AI platform built for financial services, commercial real estate, and logistics to convert unstructured bank statements, invoices, and ACORD forms into validated JSON.

- **[Nanonets](https://nanonets.com)**  
  No-code cloud OCR and workflow automation platform enabling teams to train custom document extraction models and sync structured fields directly to ERPs and databases.


## Open-Source GitHub Projects

- **[firecrawl/pdf-inspector](https://github.com)**  
  Open-source PDF inspection and document parsing utility from Firecrawl engineered to analyze PDF layouts, inspect document structure, and streamline clean text/Markdown extraction.

- **[Docling (`docling-project/docling`)](https://github.com)**  
  Flagship open-source document conversion toolkit (originally developed by IBM Research) parsing PDF, DOCX, PPTX, HTML, and images into rich unified Markdown/JSON with layout, table structure, and formula recognition.

- **[Marker (`VikParuchuri/marker`)](https://github.com)**  
  High-speed, high-accuracy open-source PDF-to-Markdown, JSON, and HTML converter powered by deep learning that cleans headers/footers, formats tables, and converts equations to LaTeX.

- **[MinerU (`opendatalab/MinerU`)](https://github.com)**  
  Comprehensive open-source scientific and multi-column PDF extraction suite (`Magic-PDF`) converting academic papers, textbooks, and complex layouts into clean Markdown and JSON.

- **[PaddleOCR (`PaddlePaddle/PaddleOCR`)](https://github.com)**  
  Industry-leading open-source multilingual OCR and document structure toolkit (`PP-Structure`) supporting 80+ languages, table recognition, layout analysis, and ultra-lightweight mobile/server models.

- **[Surya (`VikParuchuri/surya`)](https://github.com)**  
  Modern open-source document OCR and layout analysis toolkit supporting 90+ languages, line-level text detection, reading-order reconstruction, table recognition, and LaTeX math OCR.

- **[Unstructured Open Source (`Unstructured-IO/unstructured`)](https://github.com)**  
  Widely adopted open-source Python library providing modular partitioning and chunking pipelines for PDFs, Office files, emails, and images with local vision-transformer layout models.

- **[PyMuPDF & PyMuPDF4LLM (`pymupdf/PyMuPDF`)](https://github.com)**  
  Blazing-fast open-source Python bindings for MuPDF offering sub-second PDF text/image/table extraction and native LLM-ready Markdown output (`pymupdf4llm`).

- **[Tesseract OCR (`tesseract-ocr/tesseract`)](https://github.com)**  
  Foundational open-source LSTM-based OCR engine maintained by Google supporting over 100 languages, hOCR/ALTO XML output, and command-line batch processing.

- **[pdfplumber (`jsvine/pdfplumber`) & Camelot (`camelot-dev/camelot`)](https://github.com)**  
  Precision open-source Python libraries for extracting exact character coordinates, bounding boxes, and complex bordered/borderless tables from machine-generated PDFs.

- **[olmOCR (`allenai/olmocr`)](https://github.com)**  
  Open-source Vision-Language Model (VLM) PDF linearization toolkit from Allen AI engineered to convert messy scanned PDFs, equations, and multi-column layouts into natural reading-order plain text.

### Additional Strong Open-Source Options

- **[OCRmyPDF (`ocrmypdf/OCRmyPDF`)](https://github.com)** for an indispensable open-source CLI tool that adds a searchable, deskewed, lossless OCR text layer (`Tesseract`) to scanned PDF files while preserving original resolution.
- **[Kreuzberg (`Goldziher/kreuzberg`)](https://github.com)** for a lightweight, high-performance open-source text extraction library supporting PDFs, images, Office documents, and async Python/Rust pipelines.
- **[EasyOCR (`JaidedAI/EasyOCR`)](https://github.com)** and **[DocTR (`mindee/doctr`)](https://github.com)** for PyTorch/TensorFlow open-source end-to-end scene-text and document OCR models with clean Python APIs.
- **[Paperless-ngx (`paperless-ngx/paperless-ngx`)](https://github.com)** for a flagship self-hosted open-source document management system that automatically OCRs, tags, and full-text indexes scanned household and office PDFs.
- **[Nougat (`facebookresearch/nougat`)](https://github.com)** and **[pix2tex / LaTeX-OCR (`lukas-blecher/LaTeX-OCR`)](https://github.com)** for specialized open-source neural OCR converting mathematical formulas and scientific PDFs directly into LaTeX markup.

**Frameworks for building custom systems**: Combine **Docling** or **Marker / MinerU** for layout-aware PDF-to-Markdown RAG ingestion, **PaddleOCR** or **OCRmyPDF** for scanned multilingual document OCR, **pdfplumber** for deterministic financial table extraction, and **Paperless-ngx** for self-hosted searchable document archives.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Support & Share

If you find this curated list helpful, consider supporting the project:

- ⭐ **Star this repository** to help others discover it.
- 🍴 **Fork & Share** it with your team, friends, or community on X/Twitter, LinkedIn, and Reddit.
- ☕ **Buy me a coffee / Sponsor** my open-source work on [GitHub Sponsors](https://github.com) — featuring tiers for profile badges, README shoutouts, logo placements, and prioritized bug fixes/features!

[![Sponsor @ishandutta2007](https://shields.io)](https://github.com)

## Disclaimer

Use code with caution.
• This is a community-curated list — not exhaustive and not an endorsement.
• Note that PyMuPDF uses the AGPL-3.0 open-source license (with commercial licensing available from Artifex), whereas Docling (MIT), PaddleOCR (Apache 2.0), Tesseract (Apache 2.0), pdfplumber (MIT), and olmOCR (Apache 2.0) use permissive open-source licenses.
• Invoices, medical records, tax forms, and contracts processed through document intelligence pipelines contain sensitive PII; run self-hosted open-source parsers (Docling, PaddleOCR, Paperless-ngx) on private infrastructure when handling regulated data.
Made for AI/RAG engineers, data engineers, document automation teams, archival researchers, and open-source contributors.
Let's make document intelligence, PDF parsing, and OCR more open, accurate, and privacy-preserving.
