#go-color-logger

wrapper to github.com/mgutz/logxi/v1 and redirect logs to files, refer to: https://github.com/mgutz/logxi

# examples

please try...

- 1

        go run main.go
        
    
- 2

        LOGXI=*=DBG LOGXI_FORMAT=happy,t="2006-01-02 15:04:05:123.000",maxcol=180,context=-1 LOGXI_COLORS=key=cyan+h,value=magenta+h,misc=blue+h,source=magenta,TRC,DBG=yellow,WRN=yellow,INF=green,ERR=red+h,misc=blue+h go run main.go
        
- 3

        LOGXI=*=DBG LOGXI_FORMAT=JSON go run main.go
        
        
