- https://www.udemy.com/course/manual-and-automation-software-testing-with-help-of-chatgpt/learn/lecture/43343386#overview 
## Nội dung chính
- Về cơ bản thì bài này hướng dẫn ae cách dùng chatGPT để visualize test case dưới dạng bảng (Test table): Mình sẽ nhìn được test case 1 cách trực quan hơn, dễ hiểu hơn
- Ngoài ra mình cũng có thể phân loại được các test case ra các trường hợp Positive hoặc Negative: Khi phân loại được thì mình cũng sẽ dễ phát hiện được xem bộ test case có đang bị thiếu test case hay không

## Tạo Test table bằng chatGPT
- Hiểu nôm na là thể hiện test cases dưới dạng bảng giống trong file Excel
- Cách dùng:
    - Ví dụ: 
        - Bạn cần test chức năng thanh toán của 1 trang web bán vé
        - Vào ChatGPT > Nhập prompt:
            I need to create a tables for testing the purchase process of our website.
            Can you assist me in structuring test cases and organizing them into a table?
            -> Prompt này làm 2 việc: 
                - Yêu cầu chatGPT gen ra test case
                - Yêu cầu chatGPT tổ chức các test case đó dưới dạng test table

## Phân loại các test case vừa gen sang Positive test cases hoặc Negative test cases
- Vẫn sử dụng session hiện tại
- Vào chatGPT > Nhập prompt:
    I'd like to categorize them into positive and negative scenarios and strength validation showing them in a list.
    -> Prompt này sẽ phân loại các test case đã được gen ra ở prompt bên trên và đưa đưa chúng về các:
        - Positive scenario
        - Negative scenario 