# Repositorio-de-Programacion-1333123
namespace WinFormsApp1
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void button1_Click(object sender, EventArgs e)
        {

        }

        private void Form1_Load(object sender, EventArgs e)
        {

        }
    }
}

namespace WinFormsApp
{
    public class OperacionesSumatoria
    {
        public OperacionesSumatoria()
        {
            
            Console.WriteLine("Indique hasta donde desea su sumatoria: ");
            int valor = int.Parse(Console.ReadLine());
            for (int i = 1; i <= valor; i++)
            {

            }
        }

    }
}

namespace WinFormsApp
{
    public class OperacionesFactorial
    {
        public OperacionesFactorial()
        {
            Console.WriteLine ("Indique su valor factorial: ")
            int valor1 = int.Parse(Console.ReadLine());
            for (int i = 1; i <= valor1; i++)
            {
                i*= valor1;

            }
        }

    }
}

namespace WinFormsApp
{
    public class OperacionesNP
    {
        public OperacionesNP()
        {

        }

    }
}
