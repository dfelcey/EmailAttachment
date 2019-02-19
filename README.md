# Email Attachment Integration

This integration checks for emails in a mail box using the IMAP interface and then if they have a JPEG attachment it passes them to the Document Processing API an marks them as read. It does this repeatedly at a set schedule but only checks new emails that are not marked as read

