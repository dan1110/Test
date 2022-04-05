# Test

    const copyObject = () => {
        const description1 = {
          languages: {
            vi: "Xin chào",
            en: "Hello",
          },
          age: 30,
        };

        const description2 = description1;
        description2.languages.vi = "Xin chào bạn";

        console.log(description1.languages.vi); // value: Xin chào bạn
        console.log(description2.languages.vi); // value: Xin chào bạn
    };

 * Yêu cầu: chỉnh sửa lại đoạn code trên để khi thay đổi languages.vi của description2 thì description1.languages.vi vẫn là "Xin chào"
