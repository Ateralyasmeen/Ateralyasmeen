- 👋 Hi, I’m @Ateralyasmeen
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Ateralyasmeen/Ateralyasmeen is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
Public Class Form1

    Private Sub Form1_Load(sender As Object, e As EventArgs) Handles MyBase.Load

        ' إعداد واجهة المستخدم

        ' تعيين النص لعنوان التطبيق
        LabelTitle.Text = "عنوان التطبيق"

        ' تعيين صورة لخلفية التطبيق
        PictureBoxBackground.Image = Image.FromFile("background.png")

        ' تعيين وظيفة لزر تسجيل الدخول
        ButtonLogin.Click += New EventHandler(AddressOf ButtonLogin_Click)

        ' تعيين وظيفة لزر التسجيل
        ButtonRegister.Click += New EventHandler(AddressOf ButtonRegister_Click)

    End Sub

    Private Sub ButtonLogin_Click(sender As Object, e As EventArgs) Handles ButtonLogin.Click

        ' اكتب الكود الخاص بوظيفة تسجيل الدخول

    End Sub

    Private Sub ButtonRegister_Click(sender As Object, e As EventArgs) Handles ButtonRegister.Click

        ' اكتب الكود الخاص بوظيفة التسجيل

    End Sub

End Class
