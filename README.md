# Lipnet

Keras implementation of the method described in the paper 'LipNet: End-to-End Sentence-level Lipreading' by Yannis M. Assael, Brendan Shillingford, Shimon Whiteson, and Nando de Freitas (https://arxiv.org/abs/1611.01599).

### Installation Steps

<!-- - Extract the `models - checkpoint 50.zip` file and move the models folder to the parent directory -->
- Create new conda env: `conda create -n "lipnet" python=3.7 ipython`
- Activate conda env: `conda activate lipnet`
- Install requirements: `pip install -r requirements.txt`
- Install ipykernel package: `conda install ipykernel --update-deps --force-reinstall`
- Install ffmpeg: `conda install -c conda-forge ffmpeg`


### Execution of Jupyter Notebook

- Select the Python kernel as the lipnet conda env created
- Execute all cells of the Jupyter notebook. This will download the data and model checkpoints to local directory.

### Running the Streamlit UI

- Change directory to streamlit dir: `cd app`
- Run streamlit app: `streamlit run streamlitapp.py --server.port 8000`
- The UI can then be accessed on the browser at [this link](http://localhost:8000/)