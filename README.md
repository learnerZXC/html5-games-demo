# html5-games-demo
H5小游戏

## 掷骰子游戏规则
玩家扔一对骰子，两个骰子点数之和可以是2到12中的任意一个数，如果玩家第一次抛出7或者11，那么他就获胜，如果玩家抛出2、 3或12，那么他就输了，抛出其他结果（4,5,6,8,9,10），则会记录玩家点数，然后继续扔骰子，后面再抛出7就输了，而如果正好又抛出玩家的点数则获胜，对于其他情况，游戏继续，并遵循刚才的掷骰子的规则。

			let bank = Number(docunment.f.bank.value); //将一个新变量设置为bank输入域中值所表示的数
			if(bank < 10) {		//金币小于10，则无法继续
				alert("您的余额不足，请充值！");
				return;
			}
			bank = bank - 10;	//输一次金币减10
			document.f.bank.value = String(bank);


						bank = Number(document.f.bank.value);
						bank += 20;
						document.f.value = String(bank);