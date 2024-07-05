pyenv activate pytest-env39

nvm use 20

CXX=g++-10 yarn install

CXX=g++-10 yarn add sicp

sudo sed -e 's#"main" : "./lib",##' -i /home/alexgong/proj/sicp/node_modules/node-getopt/package.json

临时添加
export PATH="./node_modules/.bin:$PATH"


js-slang --chapter=2 -e "$(< js_programs/chapter2/section1/subsection1/21_example_2.1.js)"

js-slang --chapter=3 -e "$(< js_programs/chapter3/section1/subsection1/01_withdraw_example.js)"

js-slang --chapter=1 -e "$(< js_programs/chapter1/section2/subsection1/01_factorial_definition.js)"

js-slang --chapter=1 -e "$(< js_programs/chapter1/section2/subsection1/02_factorial_example.js)"

js-slang --chapter=1 -e "$(< js_programs/chapter1/section2/subsection1/04_factorial_iterative_definition.js)"





js-slang -n --chapter=2 -e "$(< 02_cons_with_dispatch.js)"