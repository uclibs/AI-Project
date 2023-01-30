# AI-Project

R&D project to extract text from a document (Word, PDF, Text, etc.) and suggest potential metadata fields for the file (title, description, subject, etc.)

Potential implementation:
1. User submits a document to Scholar@UC and adds basic metadata
1. A background job initiates an AI service that suggestes additional metadata
1. User is sent an email with option to use the suggested metadata
1. If accepted by the user, the suggested metadata is applied to the work
