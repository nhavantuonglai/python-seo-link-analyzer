# SEO Link Analyzer

(Original Vietnamese below)

_SEO Link Analyzer (SLA) is a Python tool for extracting URLs from sitemaps, scanning external links from a URL list, and detecting 404 errors. It supports XML sitemaps with regex fallback, filters external links based on a specified domain, and identifies broken links. Results are saved to text files, making it ideal for SEO audits and content analysis._

## Installation Guide

To install, run the following command in your terminal:

```
npm install seo-link-analyzer
```

## Purpose

– Extracts URLs from sitemaps for website structure analysis or content auditing.

– Scans external links from a URL list, filtering by a user-defined domain.

– Detects 404 errors from a URL list to identify broken links.

## Workflow

– Select feature: Input `1` to extract URLs from a sitemap, `2` to scan external links, `3` to detect 404 errors, or `0` to exit. No default value; users must explicitly choose the desired functionality to proceed.

– Provide input data:

For sitemap extraction, enter a sitemap URL (e.g., `https://nhavantuonglai.com/sitemap-0.xml`). A valid URL is required.

For link scanning or 404 detection, input a file path containing URLs or leave blank to use `nhavantuonglai.txt`.

– Specify domain (for link scanning): If scanning external links, enter your domain (e.g., `nhavantuonglai.com`) to filter external links, or leave blank to use `nhavantuonglai.com`. This step is skipped for sitemap extraction and 404 detection.

– Process and complete: The tool processes the input (sitemap or URL list), extracts data, and saves results to:

`nhavantuonglai.txt` (sitemap URLs)

`nhavantuonglai-output.txt` (external links)

`nhavantuonglai-404.txt` (broken links)

It displays the count of items found.

– Review results: Check the output files for extracted URLs, external links, or broken links. The tool ensures unique entries and handles errors gracefully, such as invalid sitemaps or inaccessible URLs.

## Contact & Support

– Email: info@nhavantuonglai.com.

– Website: [nhavantuonglai.com](https://nhavantuonglai.com).

If you have any questions or suggestions, don’t hesitate to contact us for the quickest support.

Don’t forget to star this repository if you find it useful.

# Công cụ phân tích liên kết SEO

_Công cụ phân tích liên kết SEO (SLA) là tiện ích Python dùng để trích xuất URL từ sitemap, quét liên kết bên ngoài từ danh sách URL, và phát hiện lỗi 404. Nó hỗ trợ sitemap XML với cơ chế dự phòng regex, lọc liên kết bên ngoài dựa trên domain chỉ định, và xác định liên kết hỏng. Kết quả được lưu vào tệp văn bản, phù hợp cho kiểm tra SEO và phân tích nội dung._

## Hướng dẫn cách cài đặt

Để cài đặt, chạy lệnh sau trong terminal:

```
npm install seo-link-analyzer
```

## Công dụng

– Trích xuất URL từ sitemap để phân tích cấu trúc website hoặc kiểm tra nội dung.

– Quét liên kết bên ngoài từ danh sách URL, lọc theo domain do người dùng chỉ định.

– Phát hiện lỗi 404 từ danh sách URL để xác định liên kết hỏng.

## Flow thao tác

– Chọn tính năng: Nhập `1` để trích xuất URL từ sitemap, `2` để quét liên kết bên ngoài, `3` để phát hiện lỗi 404, hoặc `0` để thoát. Không có giá trị mặc định; người dùng phải chọn rõ ràng chức năng mong muốn để tiếp tục.

– Cung cấp dữ liệu đầu vào:

Với trích xuất sitemap, nhập URL sitemap (Ví dụ: `https://nhavantuonglai.com/sitemap-0.xml`). Cần URL hợp lệ.

Với quét liên kết hoặc phát hiện 404, nhập đường dẫn tệp chứa URL hoặc để trống để dùng `nhavantuonglai.txt`.

– Chỉ định domain (cho quét liên kết): Nếu quét liên kết bên ngoài, nhập domain của bạn (Ví dụ: `nhavantuonglai.com`) để lọc liên kết bên ngoài, hoặc để trống để dùng `nhavantuonglai.com`. Bước này bỏ qua khi trích xuất sitemap và phát hiện 404.

– Xử lý và hoàn tất: Công cụ xử lý dữ liệu đầu vào (sitemap hoặc danh sách URL), trích xuất dữ liệu, và lưu kết quả vào:

`nhavantuonglai.txt` (URL sitemap)

`nhavantuonglai-output.txt` (liên kết bên ngoài)

`nhavantuonglai-404.txt` (liên kết hỏng)

Hiển thị số lượng mục tìm thấy.

– Xem kết quả: Kiểm tra tệp đầu ra để xem danh sách URL, liên kết bên ngoài, hoặc liên kết hỏng. Công cụ đảm bảo các mục không trùng lặp và xử lý lỗi mượt mà, như sitemap không hợp lệ hoặc URL không truy cập được.

## Liên hệ & Hỗ trợ

– Email: info@nhavantuonglai.com.

– Website: [nhavantuonglai.com](https://nhavantuonglai.com).

Nếu bạn có bất kỳ câu hỏi hoặc đề xuất nào, đừng ngần ngại liên hệ với chúng tôi để được hỗ trợ nhanh nhất.

Đừng quên star repository này nếu bạn thấy nó hữu ích.