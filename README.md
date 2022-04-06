# Neuromatch-2021_Deep-learning_Project (Contributors: Jennifer Jensen, Christopher Versteeg, Shruti Marathe,Jiaxin Cindy)
   Neural firing rates can be modeled with a dynamical system, suggesting that low-dimensional dynamics arising from connectivity within brain 
 regions are the sources of changes in neural activity. However, neurons across brain regions are also highly interconnected. The extent to which 
 neural activity is driven by local dynamics or by the activity of upstream brain regions remains unclear. To address this question, we used 
 simultaneously recorded neural firing rates from the secondary motor area (MOs) and the thalamus (TH) while mice performed a visual-perception task. 
 We hypothesized that the dynamics in MOs and TH are coupled during this motor behavior, and therefore models that attempt to predict MOs firing patterns
 would improve their performance when given information about the low-dimensional state in TH. To address this hypothesis, we compared the performance of
 two neural networks. In the baseline network, we used a recurrent autoencoder to reconstruct the firing rates of MOs from a low dimensional latent 
 representation of MOs activity. In the input network, we froze the weights of the MOs encoder of the baseline network, and provided the latent space 
 representation of MOs with low-dimensional inputs from TH,. Contrary to our predictions, the baseline model has high accuracy in predicting MOs activity 
 (mean squared error (MSE) loss = 0.02) and adding inputs from TH did not further improve the performance (MSE loss= 0.02). This suggests that intrinsic 
 dynamics in a single brain area may be sufficient in predicting neural activity. Our results are limited to only two example regions for a single example 
 session, and further studies should explore other brain areas.
 



