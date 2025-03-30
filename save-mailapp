# save-mailapp

package com.mycompany.mailapp;

import java.awt.*;
import java.awt.event.*;
import javax.swing.*;

public class MailApp  extends JFrame 
{
    Container cp;
    GridLayout g1;
    JPanel p1;
    
    JLabel mail_label;
    JTextField mail_text;
    
    JLabel sub_label;
    JTextField sub_text;
    
    JLabel mag_label;
    JTextField mag_text;
    
    JButton send_button;
    
    public static void main(String[] args) {
        MailApp app = new MailApp();
        app.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
        app.setSize(1000,1000);
        app.setVisible(true);
    }
    
    public MailApp(){
        super("202305127 junhyung_kim");
        ButtonHandler handler_button=new ButtonHandler();
        cp=getContentPane();
        g1=new GridLayout(0,4);
        cp.setLayout(g1);
        p1=new JPanel();
        
        mail_label= new JLabel("Your email : ");
        mail_label.setPreferredSize(new Dimension(100,20));
        
        mail_text= new JTextField("...");
        mail_text.setPreferredSize(new Dimension(150,20));
        
        sub_label = new JLabel("Subject : ");
        sub_label.setPreferredSize(new Dimension (100,20));
        
        sub_text = new JTextField("...");
        sub_text.setPreferredSize(new Dimension(150,20));
        
        mag_label = new JLabel("Message: ");
        mag_label.setPreferredSize(new Dimension(100,20));
        
        mag_text = new JTextField("...");
        mag_text.setPreferredSize(new Dimension(150,20));   
        
        send_button = new JButton("Send"); // 버튼 생성
        send_button.setPreferredSize(new Dimension(100, 20)); // 버튼 크기 설정
        send_button.addActionListener((ActionListener) handler_button); // 이벤트 핸들러 추가

        p1.add(mail_label); // Panel에 Label 추가   
        p1.add(mail_text);  // Panel에 TextField 추가
        p1.add(sub_label);
        p1.add(sub_text);
        p1.add(mag_label);
        p1.add(mag_text);
        p1.add(send_button); // Panel에 버튼 추가

        cp.add(p1); // Panel을 ContentPane에 추가
        
    }
}
