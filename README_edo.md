python3.12 -m venv TENSOAP
source TENSOAP/bin/activate
python -m pip install -r  requirements
cd TENSOAP/soapfast
make all
(on Mac make CC=gcc-12 all)

