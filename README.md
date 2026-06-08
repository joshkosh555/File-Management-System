# File Management System

A desktop file management application built with Python and Tkinter that helps 
you organize, tag, search, and preview your files where it's all from a clean, themeable 
interface. Beyond basic organization, it can search *inside* your documents and 
even read text from images using OCR.

## Features
- 🗂️ **Rule-Based Organization** – Define custom rules to automatically sort files 
  into categories (Documents, Images, Videos, Music) by file type
- 🏷️ **File Tagging** – Tag files for quick grouping and retrieval
- 🔍 **Content Search** – Search inside file contents using TF–IDF and cosine 
  similarity ranking, with graceful fallback to keyword matching
- 📄 **Multi-Format Text Extraction** – Reads text from PDF, DOCX, PPTX, TXT, 
  CSV, JSON, and Markdown files
- 🖼️ **Image OCR** – Extracts and searches text within images (PNG, JPG, etc.) 
  via Tesseract
- 👁️ **File Preview** – Built-in preview panel for quick inspection
- 🌙 **Light / Dark Theme** – Toggle between themes on the fly
- 📁 **Folder Management** – Save and quickly switch between favorite folders
- ♻️ **Safe Deletion** – Files moved to a local trash instead of permanent deletion
