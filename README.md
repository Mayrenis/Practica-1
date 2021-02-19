package com.company;

import javax.swing.*;
import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        // Introducir contraseña
        String contraseña="InFo12@";

        boolean acierto=false;

        for (int i=0;i<3 && !acierto;i++){
            String password= JOptionPane.showInputDialog("Introducir contraseña");

            if (password.equals(contraseña)){
                System.out.println("Contraseña aceptada");
                acierto=true;
            }
        }
    }







    }
