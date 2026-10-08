eBRC Bulk Downloader - Standalone Windows App

1. Run "eBRC Bulk Downloader.exe".
2. Select the source .xls spreadsheet.
3. Select the destination folder for the PDFs.
4. Adjust retries or timeout if needed.
5. Click Start batch.

The window is fixed at 820 x 650 pixels. Its animated background pauses while
the application is minimized.

The app opens a dedicated Chrome profile under:
%LOCALAPPDATA%\EBRCBulkDownloader\ChromeProfile

Sign in to DGFT there when requested. The app starts from the saved DGFT entry
URL, detects DGFT's generic error page, validates every PDF, skips existing
valid files, and writes remaining failures to failed_records.csv.

No Python installation is required.
