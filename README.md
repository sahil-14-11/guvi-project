# guvi-project
import java.util.ArrayList;
import java.util.Arrays;
impot java.util.List;

public class SpamFilter {


   private static final List <String>SPAM_KEYWORDS = Arrays.asList(
   "free","win","click here","urgent","limited offer","congratulation", "but now","unsubscribe","money back","prize","lotery","bonus");

  public static boolean isSpam( String emailcontent){
  String contentLower = emailContent.toLowerCase();
  for(String keyword:SPAM_KEYWORD){
  if(contentLower.contains(keywords)){
  }
  }
  return false;
  }
  public static void main (string[] args) {
  
  String email1 = "Congratulation!  You are the lucky winner pf our lottery. click here to claim your prize.";
  
  String email2 = "Hi, I hope you are well. Just wanted to follow up on the project details.";


System.out.println("Email 1 is spam;" +isSpam(email1));
System.out.println("Email 2 is spam;" +isSpam(email12);
 }
}
