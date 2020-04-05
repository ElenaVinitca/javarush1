                                                                                                 
import java.io.IOException;                                                                                                    
  import java.io.*;                                                                                                    
                                                                                                                         
/*                                                                                                     
Массивный максимум                                                                                                    
*/                                                                                                    
                                                                                                    
public class Solution {                                                                                                    
    public static void main(String[] args) throws Exception {                                                                                                    
        int[] array = initializeArray();                                                                                                    
        int max = max(array);                                                                                                    
        System.out.println(max);                                                                                                    
    }                                                                                                    
                                                                                                    
    public static int[] initializeArray() throws IOException {                                                                                                    
        BufferedReader reader = new BufferedReader(new InputStreamReader(System.in));                                                  
        int[] num = new int[20];                                                  
                                                          
        for(int i = 0; i < num.length; i ++){// создай и заполни массив                                                                                                    
        num[i] = Integer.parseInt(reader.readLine());                                                  
}                                                  
        return num;                                                                                                    
    }                                                                                                    
                                                                                                    
    public static int max(int[] array) {                                                                                                    
        int max = array[0];                                                  
        for(int i = 0; i < array.length; i ++){                                                  
         if(array[i] > max){                                                  
         max = array[i];// найди максимальное значение                                                                                                    
   }                                                  
}                                                       
        return max;                                                                                                    
    }                                                                                                    
}                                                  
                                              
