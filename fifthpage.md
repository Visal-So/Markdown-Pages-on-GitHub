## College
#### I was always wanted to go to Mizzou, but I didn't do very well on the ACT test, so I decided to take the other approche. Since I have my A+ I can go to a community college for two years to get my Associate then I can transfer to Mizzou. By doing that I can go to college for two years without costing any money at all.
#### On my first day of college I was scared. I was scared that I'm not going to be able to find my classes and ending up look like an idiot. The reason why I felt this way is because of that one video I saw online called "College Senior vs College Freshman". But it wasn't that hard, I ended up finding my classes super fast and it wasn't as complicated as I thought. MIZZOU on the other hand is a completly different story. I have to spend an entire day walking around campus to find all my classes. Beside from that College wasn't anything too different than High School. It's just that College is a different playing field. If you don't pay attention to class, the consequences is bigger than in High School.
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
![](https://github.com/Visal-So/Midterm-Project/blob/main/Images/Exam1.PNG)
#### [Home](https://github.com/Visal-So/Midterm-Project/blob/main/README.md)
#### [High School](https://github.com/Visal-So/Midterm-Project/blob/main/firstpage.md)
#### [Macon](https://github.com/Visal-So/Midterm-Project/blob/main/secondpage.md)
#### [Sports](https://github.com/Visal-So/Midterm-Project/blob/main/fourthpage.md)
#### [Travel](https://github.com/Visal-So/Midterm-Project/blob/main/thirdpage.md)
