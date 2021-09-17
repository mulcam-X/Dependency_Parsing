# Dependency_Parsing

# 사전 작업 
1. 데이터 준비 : 구문분석_말뭉치에 있는 데이터를 SejongTree2Dependency/Corpus/sejong 폴더에 옮겨 놓는다.

"1. 현대\1. 현대\1. 현대 문어\현대문어_말뭉치\구문분석_말뭉치"

# 세종코퍼스 데이터를 CoNLL-U로 변환
> python SejongToDependency.py -root_dir ./Corpus/sejong -save_file result  -head_initial ./Rules/linear_rules.txt -head_final 1