setup:
	#You may want to create an alias to automatically source this:
	# alias functop="cd ~/src/functional_intro_to_python && source ~/.func/bin/activate"
	python3 -m venv ~/.venv

install:
	pip install -r requirements.txt


lint:
	pylint --disable=R,C funclib

run:
	jupyter nbconvert notebooks/Functional_Introduction_To_Python_Section_1\(Introductory_Concepts\).ipynb --to slides --post serve


all: install lint 