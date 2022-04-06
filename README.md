# Test

    const copyObject = () => {
        const description1 = {
          languages: {
            vi: "Xin chào",
            en: "Hello",
          },
          age: 30,
        };
        
        const description2 = description1; // Đoạn code cần chỉnh sửa

        description2.languages.vi = "Xin chào bạn";

        console.log(description1.languages.vi); // value: Xin chào bạn
        console.log(description2.languages.vi); // value: Xin chào bạn
    };

 * Cho trước 1 object description1 và object description2 sẽ bằng object đã cho trước.
 * Yêu cầu: chỉnh sửa lại đoạn code trên để khi chạy dòng description2.languages.vi = "Xin chào bạn" (hoặc giá trị bất kỳ) thì description1.languages.vi vẫn là "Xin chào"
