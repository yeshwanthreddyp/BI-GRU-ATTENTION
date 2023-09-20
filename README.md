# BI-GRU-ATTENTION
Multi-label bird species classification from audio recordings using bi -gru attention framework

Bird species detection is crucial for preserving biodiversity as it helps ornithologists identify and quantify the existence of bird species in a particular region. Efficient classification of bird species is achieved by analysing the acoustic recordings of the birds. The proposed approach is a Hierarchical attention-based bidirectional GRU(gated recurrent unit) for the classification of bird species from audio recordings. The attention mechanism is used to focus on the critical aspects of the output from the hidden layers of the BIGRU model. The probability scores of the output layer are used to predict the dominant species from the audio recordings. The performance of the proposed Hierarchical attention-based BIGRU model is evaluated on the Xeno-Canto dataset and achieved the F1-Score of 0.84.

A user web interface has been created download the zip file and run these commands in cmd prompt 
pip install streamlit
cd gui
virtualenv streamlitenv
streamlitenv\Scripts\activate
pip install PyDub
streamlit run web.py

