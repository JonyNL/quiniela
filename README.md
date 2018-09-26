# quiniela
Este es el codigo realizado en Java
  ```java
public class Quinela2 {
	public static void main(String[] args) {
		char[] chars = { '1', 'x', '2' };
		int[] numChars = new int[3];
		String salida = "";
		long numRes = 0, numResVal = 0;
		for (char i : chars) {
			for (char i2 : chars) {
				for (char i3 : chars) {
					for (char i4 : chars) {
						for (char i5 : chars) {
							for (char i6 : chars) {
								for (char i7 : chars) {
									for (char i8 : chars) {
										for (char i9 : chars) {
											for (char i10 : chars) {
												for (char i11 : chars) {
													for (char i12 : chars) {
														for (char i13 : chars) {
															for (char i14 : chars) {
																salida = i + " " + i2 + " " + i3 + " " + i4 + " " + i5
																		+ " " + i6 + " " + i7 + " " + i8 + " " + i9
																		+ " " + i10 + " " + i11 + " " + i12 + " " + i13
																		+ " " + i14;
																numRes++;

																/*if (salida.replaceAll("[x2 ]", "").length() > 5
																		&& salida.replaceAll("[x2 ]", "").length() < 11
																		&& salida.replaceAll("[12 ]", "").length() > 2
																		&& salida.replaceAll("[12 ]", "").length() < 6
																		&& salida.replaceAll("[1x ]", "").length() > 3
																		&& salida.replaceAll("[1x ]", "")
																				.length() < 9) {
																	numResVal++;
																	System.out.println(salida + "Res: " + numRes);

																}*/

																numChars[0] = salida.split("1", -1).length - 1;
																numChars[1] = salida.split("x", -1).length - 1;
																numChars[2] = salida.split("2", -1).length - 1;

																if (numChars[0] > 5 && numChars[0] < 11
																		&& numChars[1] > 2 && numChars[1] < 6
																		&& numChars[2] > 3 && numChars[2] < 9) {
																	numResVal++;
																	System.out.println(salida + " 1: " + numChars[0]
																			+ " x: " + numChars[1] + " 2: "
																			+ numChars[2] + " Res: " + numRes);
																}
															}
														}
													}
												}
											}
										}
									}
								}
							}
						}
					}
				}
			}
		}
		System.out.println("NumRes: " + numRes);
		System.out.println("ResVal: " + numResVal);
	}
}  
  ```
