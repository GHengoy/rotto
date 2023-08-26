#환경세팅
터미널에 python -m venv venv 입력
cd venv/Scripts
activate (종료 시 deactivate)
cd ../../

python.exe -m pip install --upgrade pip
pip install interpret pandas numpy scikit-learn imblearn \
            hyperopt openpyxl dash dash_cytoscape \
            gevent tensorflow matplotlib