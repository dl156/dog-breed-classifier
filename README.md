# dog-classfier
# dog-classfier
pip install -U kaggle-cli

kg config -u myuser -p mypassword -c dog-breed-identification

mkdir data

cd data

mkdir dogbreed

cd dogbreed 

kg download

unzip labels.csv.zip

unzip sample_submission.csv.zip

unzip train.zip 

unzip test.zip
