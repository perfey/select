下拉选择组件
====

支持IE7+（IE7效果有小瑕疵）<br>
本组件由Bootstrap的下拉菜单改造,主要可以用来替换原生的丑陋下拉选择框<br>
注意：如果你的页面引入了Bootstrap，本组件可能会有冲突，需要调整js和css才能达到预期效果<br>
使用说明：<br>
<ul>
	<li>
		<p>基础效果，支持click，hover，禁用三种下拉框。</p>
		<p>hover形式的下拉框需要在类为dropdown的div上增加 data-type="hover" 并且在类为dropdown-toggle的a上增加 data-type="hover" </p>
		<p>禁用下拉框，需要在类为dropdown-toggle的a上增加disabled类</p>
		<p>获取选中的值，可以再点击的时候直接用js或jQuery获取到；也可以通过获取类为dropdown-toggle的a节点的data值来获取，其中data().value为选中的值，data().text为选中的文本值</p>
	</li>
</ul>