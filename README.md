# count_words

package elclipse;

public class count_words {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		String x="harsh is the best coder";
		int count=1;
		for(int i=0;i<x.length();i++) {
			if(x.charAt(i)==' ') {
				count++;                     //counting no. of spaces which no. of words.
			}
		}
		System.out.print(count);              	
	}
}

// time complexity O(N).
