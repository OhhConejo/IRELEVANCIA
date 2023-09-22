# IRELEVANCIA
private void btnCALCULAR_Click(object sender, EventArgs e)
        {
            txtT1.Visible = false; 
            txtT2.Visible = false;
            txtM.Visible = false;
            txtTheta.Visible=false;
            btnINGRESAR.Visible=false;
            label2.Visible=false;   
            label3.Visible=false;   
            label4.Visible=false; 
            label5.Visible=false; 
            label1.Visible=false;
                double theta;
                theta = Convert.ToDouble(txtTheta.Text);
                if (theta == 0)
                {
                    MessageBox.Show(" DEBES INGRESAR EL ANGULO TETA FORZOSAMENTE");
                }
                lblT1.Visible = true;
                lblT2.Visible = true;
                lblM.Visible = true;
                lblTHETA.Visible = true;
                btnCALCULAR.Visible = true;

                lblT1.Text = txtT1.Text;
                lblT2.Text = txtT2.Text;
                lblM.Text = txtM.Text;
                lblTHETA.Text = txtTheta.Text;

                //ENCONTRAR TENSION 2 Y MASA
                if (lblM.Text & lblT2 == " ")
                {
                    double Theta = double.Parse(txtTheta.Text);
                    double Masa = double.Parse(txtM.Text);
                    double Tension1 = double.Parse(txtT1.Text);
                    double Tension2 = double.Parse(txtT2.Text);

                    Tension2 = Tension1 / Math.Cosh(Theta)
                     Masa = Tension2 * Math.Sin(Theta);


                    txtTheta.Text = Theta.ToString();
                    txtT1.Text = Tension1.ToString();
                    txtT2.Text = Tension2.ToString();
                    MessageBox.Show("LA TENSION 2 ES DE " + txtT2.Text + "LA MASA ES DE: " + txtM.Text);
                }

                //ENCONTRAR TENSION 1 Y MASA
                if (lblM.Text & lblT2 == " ")
                {

                    double Theta = double.Parse(txtTheta.Text);
                    double Masa = double.Parse(txtM.Text);
                    double Tension1 = double.Parse(txtT1.Text);
                    double Tension2 = double.Parse(txtT2.Text);


                    Masa = Tension2 * Math.Sin(Theta);
                    Tension1 = Tension2 * Math.Cos(Theta);


                    txtTheta.Text = Theta.ToString();
                    txtT1.Text = Tension1.ToString();
                    txtT2.Text = Tension2.ToString();
                    MessageBox.Show("LA TENSION 1 ES DE " + txtT1.Text + "LA MASA ES DE: " + txtM.Text);
                }

                //ENCONTRAR AMBAS TENSIONES
                if (lbT1.Text & lblT2 == " ")
                {

                    double Theta = double.Parse(txtTheta.Text);
                    double Masa = double.Parse(txtM.Text);
                    double Tension1 = double.Parse(txtT1.Text);
                    double Tension2 = double.Parse(txtT2.Text);


                    Tension2 = Masa / Math.Sin(Theta);
                    Tension1 = Tension2 * Math.Cos(Theta);


                    txtTheta.Text = Theta.ToString();
                    txtT1.Text = Tension1.ToString();
                    txtT2.Text = Tension2.ToString();
                    MessageBox.Show("LA TENSION 1 ES DE " + txtT1.Text + "LA TENSION 2 ES DE: " + txtT2.Text);
                }






            

        }
