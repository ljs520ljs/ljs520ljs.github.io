<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<title>表单</title>
	</head>
	<body>
		<form name="formi" method="get" action="" enctype="multipart/form-data">
			<p>文本框
				<input type="text" name="username" value="小明" size="20" />
			</p>
			<p>密码框
				<input type="password" name="pwd" value="2025" size="20" />
			</p>
			<p>单选按钮
				<input type="radio" name="sex" value="男" checked="checked" />男
				<input type="radio" name="sex" value="女" />女
			</p>
			<p>选妃按钮
				<input type="checkbox" name="ch1" value="basketball" />少萝
				<input type="checkbox" name="ch2" value="football" />御姐
				<input type="checkbox" name="ch3" value="volleyball" />幼女
				<input type="checkbox" name="ch4" value="pingpangball" />极品大学生
			</p>
			<p>按钮
				<input type="submit" name="s1" value="提交" />
				<input type="reset" name="r1" value="重置" />
				<input type="button" name="b1" value="按钮" />
			</p>
			<p>想和她在哪里
				<select name="seasons">
					<option value="" selected="selected">选择</option>
					<option value="1">酒店</option>
					<option value="2">家里</option>
					<option value="3">宾馆</option>
					<option value="4">小树林</option>
				</select>
			</p>
			<p>喜欢什么风格
				<select name="seasons">
					<option value="" selected="selected">选择</option>
					<option value="1">可爱型</option>
					<option value="2">温柔型</option>
					<option value="3">撒娇型</option>
					<option value="4">听话型</option>
				</select>
			</p>
			<p>
				<input type="file" name="files" />
			</p>
		</form>
		<h2>只是单纯调研哦</h2>
	</body>
</html>
