<!DOCTYPE html>

<html xmlns="http://www.w3.org/1999/xhtml">
<head runat="server">
    <title></title>
    <style type="text/css">
        .auto-style1 {
            font-size: xx-large;
        }
        .auto-style2 {
            text-align: center;
        }
        .auto-style3 {
            width: 100%;
        }
        .auto-style5 {
            width: 655px;
            height: 62px;
        }
        .auto-style7 {

            width: 655px;
            height: 63px;
        }
        .auto-style8 {
            height: 63px;
            text-align: left;
        }
        .auto-style9 {
            width: 655px;
            height: 66px;
        }
        .auto-style10 {
            height: 66px;
            text-align: left;
        }
        .auto-style11 {
            width: 655px;
            height: 62px;
            text-align: center;
        }
        .auto-style12 {
            height: 62px;
            text-align: left;
        }
    </style>
</head>
<body>
    <form id="form1" runat="server">
        <div>
        </div>
        <div class="auto-style2" style="background-image: url('https://localhost:44308/rage_123.jpg')">
            <asp:Image ID="Image1" runat="server" Height="221px" ImageUrl="~/raje_gp.PNG" Width="381px" />
&nbsp;<strong><span class="auto-style1">RAJE GRUOP VIGHVALI</span>
    <table class="auto-style3">
                <tr>
                    <td class="auto-style11">ID:</td>
                    <td class="auto-style12">
                        <asp:TextBox ID="TextBox1" runat="server" Height="35px" Width="301px"></asp:TextBox>
                    </td>
                </tr>
                <tr>
                    <td class="auto-style5">NAME:</td>
                    <td class="auto-style12"><strong>
                        <asp:TextBox ID="TextBox2" runat="server" Height="35px" Width="301px"></asp:TextBox>
                        </strong></td>
                </tr>
                <tr>
                    <td class="auto-style11">CONTACT_NUMBER</td>
                    <td class="auto-style12"><strong>
                        <asp:TextBox ID="TextBox3" runat="server" Height="35px" Width="301px"></asp:TextBox>
                        </strong></td>
                </tr>
                <tr>
                    <td class="auto-style5">BATSMAN</td>
                    <td class="auto-style12">
                        <asp:DropDownList ID="DropDownList1" runat="server">
                            <asp:ListItem Text="SELECT" Value="SELECT" Selected="True"></asp:ListItem>
                            <asp:ListItem Text="YES" Value="YES"></asp:ListItem>
                            <asp:ListItem Text="NO" Value="NO"></asp:ListItem>
                         </asp:DropDownList>
                    </td>
                </tr>
                <tr>
                    <td class="auto-style7">BOWLING</td>
                    <td class="auto-style8">
                        <asp:DropDownList ID="DropDownList2" runat="server">
                            <asp:ListItem Text="SELECT" Value="SELECT" Selected="True"></asp:ListItem>
                             <asp:ListItem Text="YES" Value="YES"></asp:ListItem>
                             <asp:ListItem Text="NO" Value="NO"></asp:ListItem>
                        </asp:DropDownList>
                    </td>
                </tr>
                <tr>
                    <td class="auto-style9">ALL-ROUNDER</td>
                    <td class="auto-style10">
                        <asp:DropDownList ID="DropDownList3" runat="server">
                          <asp:ListItem Text="SELECT" Value="SELECT" Selected="True"></asp:ListItem>
                             <asp:ListItem Text="YES" Value="YES"></asp:ListItem>
                             <asp:ListItem Text="NO" Value="NO"></asp:ListItem>
                        </asp:DropDownList>
                    </td>
                </tr>
                <tr>
                    <td class="auto-style9">AGE</td>
                    <td class="auto-style10">
                        <strong>
                        <asp:TextBox ID="TextBox4" runat="server" Height="35px" Width="301px"></asp:TextBox>
                        </strong>
                    </td>
                </tr>
                <tr>
                    <td class="auto-style9">&nbsp;</td>
                    <td class="auto-style10">
                        <asp:Button ID="Button1" runat="server" Text="SUBMIT" OnClick="Button1_Click" />
                    </td>
                </tr>
            </table>
            </strong>
        </div>
    </form>
</body>
</html>
