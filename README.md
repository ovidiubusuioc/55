TEXT CLIENT 
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package seriaC.poo.client;

import java.io.BufferedReader;
import java.io.IOException;
import java.io.InputStreamReader;
import java.net.Socket;
import java.util.logging.Level;
import java.util.logging.Logger;

/**
 *
 */
public class TextClient {
    public static void main(String[] args){
        //ClientPeer cp = new ClientPeer(expeditorul, socket);
        
        BufferedReader in = new BufferedReader(new InputStreamReader(System.in));
        
        String tring = new String();
        
        try {
            tring = in.readLine();
        } catch (IOException ex) {
            Logger.getLogger(TextClient.class.getName()).log(Level.SEVERE, null, ex);
        }
        
        System.out.println(tring);
        
    }
}

CLIENTPEER
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package seriaC.poo.client;

import java.net.Socket;

/**
 *
 */
public class ClientPeer {
    ClientPeer (String expeditorul, Socket socket){
        
    }
    void sendMessage(String message){
        //Message meaaj = new Message();
        
    }
    void sendMessage(String message, String recipient){
        //PrivateMessage mesaj = new PrivateMessage();
    }
    
}



