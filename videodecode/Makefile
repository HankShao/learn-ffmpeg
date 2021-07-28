CFLAG := -I/home/hank/Desktop/share/opensource/learn-ffmpeg/include
LDFLAG := -L/home/hank/Desktop/share/opensource/learn-ffmpeg/lib -lavdevice -lavfilter -lpostproc -lavformat -lavcodec -lxcb-shm -lxcb-xfixes -lxcb-render -lxcb-shape -lxcb -lXau -lx265 -lstdc++ -lrt -lx264 -ldl -lpthread -lopus -lfreetype -lbz2 -lz -lswresample -lswscale -lavutil  -lX11 -lm -lva -lva-drm -lva-x11
SRC=*.c
TARGET=videotest
all:
	gcc -o $(TARGET) $(SRC) $(CFLAG) $(LDFLAG)

clean:
	rm -f $(TARGET)
