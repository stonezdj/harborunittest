Unit test env for harbor

git clone git@github.com:stonezdj/harborunittest.git

cd harborunittest

./cleanut.sh

cd <path/to/harbor/src>
go test ./src/common/core/api/... -v
