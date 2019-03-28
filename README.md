 public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void lstFrutas_SelectedIndexChanged(object sender, EventArgs e)
        {
            //Adicionar Elementos
           /* lstFrutas.Items.Add("Banana");
            lstFrutas.Items.Add("Durazno");*/
        }

        private void Adicionar_Click(object sender, EventArgs e)
        {
            lstFrutas.Items.Add(textFruta.Text);
            textFruta.Text= "";
        }

        private void textFruta_TextChanged(object sender, EventArgs e)
        {

        }
    }
}



