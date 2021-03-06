package Test2;

import java.util.Scanner;

public class Biscuits {
	public static void main(String[] args) {
	 	//1.定义变量
		Scanner scan = new Scanner(System.in);
		int box;
		int container;
		int Biscuits;
		float boxrate;
		float containerate;
		//2.为变量赋值
		boxrate = 24f;
		containerate = 75f;

		int Biscuitsplus;
		int Boxplus;

		System.out.print("请输入饼干总数：");

		Biscuits = scan.nextInt();
		//3.运算处理
		box = (int) (Biscuits / boxrate);
		container = (int) (box / containerate);

		Biscuitsplus = (int) (Biscuits % boxrate);
		Boxplus = (int) (box % containerate);
		// 4.结果输出
		System.out.println("盒子的数量是：" + box);
		System.out.println("容器的数量是：" + container);
		System.out.println("多余饼干数量为：" + Biscuitsplus);
		System.out.println("多余盒子的数量为：" + Boxplus);
	}

}
