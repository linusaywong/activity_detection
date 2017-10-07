CC=g++
CV=-I/usr/include/opencv
#CV2=-lml -lcvaux -lhighgui -lcv -lcxcore
CV2=`pkg-config --libs opencv`

all:
	$(CC) -std=c++03 main.cpp HOG.cpp HOGFeaturesOfBlock.cpp $(CV) $(CV2) -o featureExtractor

