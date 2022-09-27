# 第1次作業-作業-HW1
>
>學號：109111130 
><br />
>姓名：林庭宇 
><br />
>作業撰寫時間：120 (mins，包含程式撰寫時間)
><br />
>最後撰寫文件日期：2022/9/27
>

本份文件包含以下主題：(至少需下面兩項，若是有多者可以自行新增)
- [x]說明內容
- [x]個人認為完成作業須具備觀念

## 說明程式與內容

輸出文字"Hello App"，點擊按鈕輸出文字"Hello Button"

```csharp
    public partial class Test : System.Web.UI.Page
    {
        protected void Page_Load(object sender, EventArgs e)
        {
            Response.Write("Hello App");
        }

        protected System.Void Button1_Click(System.Object sender, System.EventArgs e)
        {
            Response.Write("Hello Button");
        }
    }
}
```

若要於內文中標示部分.aspx檔，則使用以下標籤` ```html 程式碼 ``` `，
下段程式碼則為使用後結果：

```html
<%@ Page Language="C#" AutoEventWireup="true" ...>

<!DOCTYPE html>

<html xmlns="http://www.w3.org/1999/xhtml">
<head runat="server">
<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
    <title></title>
</head>
<body>
    <form id="form1" runat="server">
        <div>
            <asp:Button ID="btn_Show" runat="server" Text="Button" OnClick="Button1_Click" />
        </div>
    </form>
</body>
</html>
```


## 個人認為完成作業須具備觀念

要有一點點基礎的程式語言，上課也要稍微聽課，以免會花大量時間去蒐集資料，雖然看似簡單但其中的內容也要搞懂才能銀刃而解。

