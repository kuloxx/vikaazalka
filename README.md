// MainForm.cs - Главная форма приложения
using System;
using System.Windows.Forms;

namespace GitMergeExample
{
    public partial class MainForm : Form
    {
        public MainForm()
        {
            InitializeComponent();
            Button button1 = new Button();
            button1.Text = "Hello, Git!";
            button1.Click += (sender, e) => MessageBox.Show("Main form button clicked");
            Controls.Add(button1);
        }
    }
}
