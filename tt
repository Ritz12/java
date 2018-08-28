package JAVA_8;

import java.io.BufferedWriter;
import java.io.IOException;
import java.nio.file.Files;
import java.nio.file.Path;
import java.nio.file.Paths;

/**
 * Created by Ritu on 8/26/18.
 */
public class Testing123 {
    public static void main(String[] args) {
        Path path = Paths.get("/Users/Ritu/repo/output.txt");

//Use try-with-resource to get auto-closeable writer instance
        try (BufferedWriter writer = Files.newBufferedWriter(path)) {
            for (int i = 1; i<100000; i++) {
                writer.write("Hello World !! -> "+i + "\n");
            }
        }
        catch  (IOException e) {
            e.printStackTrace();
        }


    }
}
