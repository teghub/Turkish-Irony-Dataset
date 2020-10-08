# Acknowledgements

We benefit from the following github repository:<br />
https://github.com/ThilinaRajapakse/pytorch-transformers-classification <br />
We reimplemented the codes to add weight freezing and 10-fold cross-validation features.


# Execution
First, you need to execute "data_prep.py" to convert your csv file into .tsv files. After that, you can execute "run_model.py" to evaluate your model. Statistics related to the evaluation results are saved in "outputs" directory. 

# Turkish-Irony-Dataset
Turkish Social Media Dataset for Irony Detection

## Statistics
This dataset includes a total of 220 Turkish microblog texts, with two `.txt` files, each having 110 ironic and non-ironic sentences. Classification is made by a majority voting of 3. All data is retrieved from Turkish social media portals. 

### `ironic.txt`
* Contains 110 lines, each line having only one attribute, the sentence itself.
* First 101 lines are in lexicographical order and do not have any Emoji’s or emoticons.
* Remaining 9 lines have Emoji’s or emoticons and they are not specifically ordered.

### `non-ironic.txt`
* Contains 110 lines, each line having only one attribute, the sentence.
* First 99 lines are in lexicographical order and do not have any Emoji’s or emoticons.
* Remaining 11 lines have Emoji’s or emoticons and they are not specifically ordered.

# Citing: 
Y.Cemek, C. Cidecio, A.U.Ozturk, R.F.Cekinel, P.Karagoz, "Türkçe Resmi Olmayan Metinlerde İroni Tespiti için Sinirsel Yöntemlerin İncelenmesi (Investigating the Neural Models for Irony Detection on Turkish Informal Texts)",  in IEEE 28th Signal Processing and Communications Applications Conference (SIU), Apr 2020.
