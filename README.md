Программа 1: 
using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace WindowsFormsApp2
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void button1_Click(object sender, EventArgs e)
        {
            double x = 0;
            double y = 0;
            x = Convert.ToDouble(textBox4.Text);
            y = Convert.ToDouble(textBox2.Text);
            if (x * x + y * y < 100 && x * x + y * y > 25 && y >= 0)
            {
                MessageBox.Show("Точка находится внути закрашенной области");
            }
            else if (x * x + y * y == 100 || x * x + y * y == 25 && y >= 0)
            {
                MessageBox.Show("Точка находится на границе закрашенной области");
            }
            else
            {
                MessageBox.Show("Точка находится ВНЕ закрашенной области");
            }
        } 
        private void button2_Click(object sender, EventArgs e)
        {
            textBox4.Text = ""; textBox2.Text = "";
        }
        
        private void label3_Click(object sender, EventArgs e)
        {
           

        }

        private void Form1_Load(object sender, EventArgs e)
        {

        }

        private void textBox1_TextChanged(object sender, EventArgs e)
        {

        }
    }
}
Программа 2: 
using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace WindowsFormsApp2
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void button1_Click(object sender, EventArgs e)
        {
            double n = 0;
            n = Convert.ToDouble(textBox4.Text);
            if (n <= 31)
            {
                switch (n)
                {
                    case 1: MessageBox.Show("До конца месяца: 30"); break;
                    case 2: MessageBox.Show("До конца месяца: 29"); break;
                    case 3: MessageBox.Show("До конца месяца: 28"); break;
                    case 4: MessageBox.Show("До конца месяца: 27"); break;
                    case 5: MessageBox.Show("До конца месяца: 26"); break;
                    case 6: MessageBox.Show("До конца месяца: 25"); break;
                    case 7: MessageBox.Show("До конца месяца: 24"); break;
                    case 8: MessageBox.Show("До конца месяца: 23"); break;
                    case 9: MessageBox.Show("До конца месяца: 22"); break;
                    case 10: MessageBox.Show("До конца месяца: 21"); break;
                    case 11: MessageBox.Show("До конца месяца: 20"); break;
                    case 12: MessageBox.Show("До конца месяца: 19"); break;
                    case 13: MessageBox.Show("До конца месяца: 18"); break;
                    case 14: MessageBox.Show("До конца месяца: 17"); break;
                    case 15: MessageBox.Show("До конца месяца: 16"); break;
                    case 16: MessageBox.Show("До конца месяца: 15"); break;
                    case 17: MessageBox.Show("До конца месяца: 14"); break;
                    case 18: MessageBox.Show("До конца месяца: 13"); break;
                    case 19: MessageBox.Show("До конца месяца: 12"); break;
                    case 20: MessageBox.Show("До конца месяца: 11"); break;
                    case 21: MessageBox.Show("До конца месяца: 10"); break;
                    case 22: MessageBox.Show("До конца месяца: 9"); break;
                    case 23: MessageBox.Show("До конца месяца: 8"); break;
                    case 24: MessageBox.Show("До конца месяца: 7"); break;
                    case 25: MessageBox.Show("До конца месяца: 6"); break;
                    case 26: MessageBox.Show("До конца месяца: 5"); break;
                    case 27: MessageBox.Show("До конца месяца: 4"); break;
                    case 28: MessageBox.Show("До конца месяца: 3"); break;
                    case 29: MessageBox.Show("До конца месяца: 2"); break;
                    case 30: MessageBox.Show("До конца месяца: 1"); break;
                    case 31: MessageBox.Show("До конца месяца: 0"); break;
                    default:
                        MessageBox.Show("ВЫ ОШИБЛИСЬ"); break;

                }
            }
            else
            {
                MessageBox.Show("число превышает количество дней в месяце ");
            }
        }

        private void button2_Click(object sender, EventArgs e)
        {
            textBox4.Text = ""; 
        }
        
        private void label3_Click(object sender, EventArgs e)
        {
           

        }

        private void Form1_Load(object sender, EventArgs e)
        {

        }
    }
}
        
Программа 3: 
using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace WindowsFormsApp2
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void button1_Click(object sender, EventArgs e)
        {
            string str="";
            for (int k = 10; k <= 25; k++)
            {
                str += (k + " " + (k + 0.4)+"\n");
            }

            MessageBox.Show(str);


        }
        private void button2_Click_1(object sender, EventArgs e)
        {
            string str = "";
            int j = 10;
            do
            {
                str += (j + " " + (j + 0.4) + "\n");
                j++;
            } while (j <= 25);
            MessageBox.Show(str);
        }

        private void button3_Click(object sender, EventArgs e)
        {
            string str = "";
            int i = 10;
            while (i <= 25)
            {
                str+=(i + " " + (i + 0.4) + "\n");
                i++;
            }
            MessageBox.Show(str);
        }
        private void Form1_Load(object sender, EventArgs e)
        {

        }

       
    }
}
Программа 4: 
using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace WindowsFormsApp2
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void button1_Click(object sender, EventArgs e)

        { 
		string str="";
            for (int j = 1; j <= 5; j++)
            {
                for (int i = -10; i <= 12; i++)
                    {
                    str +=(" " + i);
                    }
               str +=(" \n")
            }
            MessageBox.Show(str);


        }
        private void button2_Click_1(object sender, EventArgs e)
        {
            
        }

        private void Form1_Load(object sender, EventArgs e)
        {

        }

       
    }
}
