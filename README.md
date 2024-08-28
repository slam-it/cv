# cv

Export md file to html using Typora (HTML without styles)
Go to https://pdfcrowd.com/html-to-pdf/ and upload zip archive containing html and images

curl -f -u "demo:ce544b6ea52a5621fb9d55f8b542d14d" \
    -o "result.pdf" \
    -F "page_size=A4" \
    -F "margin_top=0" \
    -F "margin_right=0" \
    -F "margin_bottom=0" \
    -F "margin_left=0" \
    -F "content_viewport_width=large" \
    -F "file=@Archive.zip" \

