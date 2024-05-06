FROM ubuntu:latest

RUN apt update -y
RUN apt upgrade -y
RUN apt install git -y
RUN apt install make -y
RUN apt install g++ -y
RUN git clone https://github.com/Mvrouvne/BitcoinPriceChecker.git
WORKDIR BitcoinPriceChecker/
RUN make

CMD ["./BTCchecker" ]