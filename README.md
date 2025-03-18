// FeatureForm.cs - Дополнительная форма с другим функционалом
using System;
using System.Windows.Forms;

namespace GitMergeExample
{
    public partial class FeatureForm : Form
    {
        public FeatureForm()
        {
            InitializeComponent();
            Button button2 = new Button();
            button2.Text = "New Feature!";
            button2.Click += (sender, e) => MessageBox.Show("Feature form button clicked");
            Controls.Add(button2);
        }
    }
}
