# Sitemap and link extractor

(Original Vietnamese below)

_Sitemap and link extractor (SLE) is a Python tool for extracting URLs from sitemaps or scanning external links from a URL list. It supports XML sitemaps with regex fallback and filters external links based on a specified domain. Results are saved to text files, ideal for SEO and content analysis._

## Installation Guide

To install, run the following command in your terminal:

```
npm install sitemap-extractor
```

## Purpose

– Extracts URLs from sitemaps for website structure analysis or content auditing.

– Scans external links from a URL list, filtering by a user-defined domain.

## Workflow

– Select feature: Input `1` to extract URLs from a sitemap, `2` to scan external links, or `0` to exit. No default value; users must explicitly choose the desired functionality to proceed.

– Provide input data: For sitemap extraction, enter a sitemap URL ( `https://nhavantuonglai.com/sitemap-0.xml`) with no default; a valid URL is required. For link scanning, input a file path containing URLs or leave blank to use `nhavantuonglai.txt`.

– Specify domain (for link scanning): If scanning links, enter your domain (`nhavantuonglai.com`) to filter external links, or leave blank to use `nhavantuonglai.com`. This step is skipped for sitemap extraction.

– Process and complete: The tool processes the input (sitemap or URL list), extracts data, and saves results to `nhavantuonglai.txt` (sitemap URLs) or `nhavantuonglai-output.txt` (external links). It displays the count of items found.

– Review results: Check the output files for extracted URLs or links. The tool ensures unique entries and handles errors gracefully, such as invalid sitemaps or inaccessible URLs.

## Contact & support

– Email: info@nhavantuonglai.com.

– Website: [nhavantuonglai.com](https://nhavantuonglai.com).

If you have any questions or suggestions, don't hesitate to contact us for the quickest support.

Don't forget to star this repository if you find it useful.

# Công cụ trích xuất sitemap và liên kết bên ngoài

_Công cụ trích xuất sitemap và liên kết bên ngoài (SLE) là tiện ích Python dùng để trích xuất URL từ sitemap hoặc quét liên kết bên ngoài từ danh sách URL. Nó hỗ trợ sitemap XML với cơ chế dự phòng regex và lọc liên kết bên ngoài dựa trên domain chỉ định. Kết quả được lưu vào tệp văn bản, phù hợp cho SEO và phân tích nội dung._

## Hướng dẫn cách cài đặt

Để cài đặt, chạy lệnh sau trong terminal:

```
npm install sitemap-extractor
```

## Công dụng

– Trích xuất URL từ sitemap để phân tích cấu trúc website hoặc kiểm tra nội dung.

– Quét liên kết bên ngoài từ danh sách URL, lọc theo domain do người dùng chỉ định.

## Flow thao tác

– Chọn tính năng: Nhập `1` để trích xuất URL từ sitemap, `2` để quét liên kết bên ngoài, hoặc `0` để thoát. Không có giá trị mặc định; người dùng phải chọn rõ ràng chức năng mong muốn để tiếp tục.

– Cung cấp dữ liệu đầu vào: Với trích xuất sitemap, nhập URL sitemap (Ví dụ: `https://nhavantuonglai.com/sitemap-0.xml`), không có mặc định; cần URL hợp lệ. Với quét liên kết, nhập đường dẫn tệp chứa URL hoặc để trống để dùng `nhavantuonglai.txt`.

– Chỉ định domain (cho quét liên kết): Nếu quét liên kết, nhập domain của bạn (Ví dụ: `nhavantuonglai.com`) để lọc liên kết bên ngoài, hoặc để trống để dùng `nhavantuonglai.com`. Bước này bỏ qua khi trích xuất sitemap.

– Xử lý và hoàn tất: Công cụ xử lý dữ liệu đầu vào (sitemap hoặc danh sách URL), trích xuất dữ liệu, và lưu kết quả vào `nhavantuonglai.txt` (URL sitemap) hoặc `nhavantuonglai-output.txt` (liên kết bên ngoài). Hiển thị số lượng mục tìm thấy.

– Xem kết quả: Kiểm tra tệp đầu ra để xem danh sách URL hoặc liên kết. Công cụ đảm bảo các mục không trùng lặp và xử lý lỗi mượt mà, như sitemap không hợp lệ hoặc URL không truy cập được.

## Liên hệ & hỗ trợ

– Email: info@nhavantuonglai.com.

– Website: [nhavantuonglai.com](https://nhavantuonglai.com).

Nếu bạn có bất kỳ câu hỏi hoặc đề xuất nào, đừng ngần ngại liên hệ với chúng tôi để được hỗ trợ nhanh nhất.

Đừng quên star repository này nếu bạn thấy nó hữu ích.