---
title: "How to JAVA star shrape typing"
date: 2018-9-28 09:26:28 -0400
categories: Java Developer Program CSS PHP
---

-----------------------------------------------------------------


숫자를 입력받아 1부터 입력받은 수까지 홀수의 합과 짝수의 합을 구하세요.

		int num1 = 0, num2 = 0;
		for (int i = 1; i < 21; i++) {
			if (i % 2 == 0) {
				num1 += i;
			} else if (i % 2 != 0) {
				num2 += i;
			}
		}

-----------------------------------------------------------------
직각이 오른쪽에 있는 삼각형 모양의 별을 출력해주세요.

		for (int i = 1; i < 6; i++) {
			for (int j = 5; j > 0; j--) {
				if (i < j) {
					System.out.print(" ");
				} else {
					System.out.print("*");
				}
			}
			System.out.println();
		}
		System.out.println();

-----------------------------------------------------------------
직각이 오른쪽에 있는 역삼각형 모양의 별을 출력해주세요.

		for (int i = 0; i < 5; i++) {
			for (int j = 0; j < i; j++) {
				System.out.print(" ");
			}
			for (int j = 0; j < 5 - i; j++) {
				System.out.print("*");
			}
			System.out.println();
		}

-----------------------------------------------------------------
이등변 삼각형 모양의 별을 출력해주세요.

		for (int i = 0; i < 4; i++) {
			for (int j = 0; j < 3 - i; j++) {
				System.out.print(" ");
			}
			for (int j = 0; j < 2 * i + 1; j++) {
				System.out.print("*");
			}
			System.out.println();
		}
		
		System.out.println();

		

-----------------------------------------------------------------
역 이등변 삼각형 모양의 별을 출력해주세요.
		int k1 = 0, k2 = 9;

		for (int i = 0; i < 5; i++) {

			for (int j = 0; j < k1; j++) {
				System.out.print(" ");
			}

			for (int j = 0; j < k2; j++) {
				System.out.print("*");
			}

			k1++;
			k2 -= 2;

			System.out.println();

		}
	}
}



<Html>
	<body>
		
<div id="disqus_thread"></div>
<script>

/**
*  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
*  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables*/
/*
var disqus_config = function () {
this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
};
*/
(function() { // DON'T EDIT BELOW THIS LINE
var d = document, s = d.createElement('script');
s.src = 'https://web1-kcjoeoq7q7.disqus.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>


      </body>
</html>
