## College
#### I was always wanted to go to Mizzou, but I didn't do very well on the ACT test, so I decided to take the other approche. Since I have my A+ I can go to a community college for two years to get my Associate then I can transfer to Mizzou. By doing that I can go to college for two years without costing any money at all.
#### I Major in Information Technology, Programming. At first I don't know how I feel about going into the IT field but my parent are one who push me into it. I took a programming class in High School so I know what Programming is. The first language I expirience with was C#. My first ever project is Hello World and my first exam was converting feet to yards. This is the code for that:

    public partial class Form1 : Form
    {
        double feet, yard;

        public Form1()
        {
            InitializeComponent();
        }

        private void button1_Click(object sender, EventArgs e)
        {

            if (txtbxfeet.Text == string.Empty)
            {
                lblErrorMessage.Text = "";
            }
            else
            {
                try
                {
                    feet = double.Parse(txtbxfeet.Text);
                }
                catch
                {
                    lblErrorMessage.Text = "";
                }

                yard = feet / 3;

                lblMessage.Text = feet + " feet is " + yard.ToString(".00") + " yards";
            }
        }

        private void button2_Click(object sender, EventArgs e)
        {
            this.Close();
        }
    }
#### [Home](https://github.com/Visal-So/Midterm-Project/blob/main/README.md)
#### [High School](https://github.com/Visal-So/Midterm-Project/blob/main/firstpage.md)
#### [Macon](https://github.com/Visal-So/Midterm-Project/blob/main/secondpage.md)
#### [Sports](https://github.com/Visal-So/Midterm-Project/blob/main/fourthpage.md)
#### [Travel](https://github.com/Visal-So/Midterm-Project/blob/main/thirdpage.md)
