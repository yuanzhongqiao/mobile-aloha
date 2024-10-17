<div class="Box-sc-g0xbh4-0 QkQOb js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto" _msttexthash="183603381" _msthash="225">移动 ALOHA：通过低成本的全身远程操作学习双手移动操作</h1><a id="user-content-mobile-aloha-learning-bimanual-mobile-manipulation-with-low-cost-whole-body-teleoperation" class="anchor" aria-label="永久链接： 移动 ALOHA：通过低成本全身远程操作学习双手移动操作" href="#mobile-aloha-learning-bimanual-mobile-manipulation-with-low-cost-whole-body-teleoperation" _mstaria-label="6196060" _msthash="226"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto" _msttexthash="23785606" _msthash="227">项目网址：<a href="https://mobile-aloha.github.io/" rel="nofollow" _istranslated="1">https://mobile-aloha.github.io/</a></h4><a id="user-content-project-website-httpsmobile-alohagithubio" class="anchor" aria-label="永久链接： 项目网站： https://mobile-aloha.github.io/" href="#project-website-httpsmobile-alohagithubio" _mstaria-label="2382003" _msthash="228"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="2234137906" _msthash="229">此代码库是从 <a href="https://github.com/tonyzhaozh/aloha" _istranslated="1">ALOHA 存储库</a>分叉而来的，其中包含使用 Mobile ALOHA 硬件进行远程操作和数据收集的实现。
要构建 ALOHA，请按照下面的<a href="https://docs.google.com/document/d/1_3yhWjodSNNYlpxkRCPIlvIAaQ76Nqk2wsqhnEVM6Dc" rel="nofollow" _istranslated="1">硬件组装教程</a>和快速入门指南进行操作。
要训练模仿学习算法，您还需要安装从 <a href="https://github.com/tonyzhaozh/act" _istranslated="1">ACT</a> 分叉而来的 <a href="https://github.com/MarkFzp/act-plus-plus" _istranslated="1">ACT for Mobile ALOHA</a>。</p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="15118233" _msthash="230">存储库结构</h3><a id="user-content-repo-structure" class="anchor" aria-label="永久链接： Repo Structure" href="#repo-structure" _mstaria-label="563433" _msthash="231"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><code>config</code><font _mstmutation="1" _msttexthash="381189614" _msthash="232">：每个机器人的配置，指定它们应该绑定到的端口，更多详细信息请参阅快速入门指南。</font></li>
<li><code>launch</code><font _mstmutation="1" _msttexthash="105873924" _msthash="233">：所有 4 个相机和所有 4 个机器人的 ROS 启动文件。</font></li>
<li><code>aloha_scripts</code><font _mstmutation="1" _msttexthash="71569368" _msthash="234">：用于 Teleop 和数据收集的 Python 代码</font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="20451847" _msthash="235">快速入门指南</h2><a id="user-content-quick-start-guide" class="anchor" aria-label="永久链接：快速入门指南" href="#quick-start-guide" _mstaria-label="644995" _msthash="236"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="48548851" _msthash="237">软件选择 -- 操作系统：</h3><a id="user-content-software-selection----os" class="anchor" aria-label="永久链接： 软件选择 -- 操作系统：" href="#software-selection----os" _mstaria-label="882544" _msthash="238"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="49332062" _msthash="239">当前测试和工作配置：</p>
<ul dir="auto">
<li _msttexthash="1362985" _msthash="240">✅ Ubuntu 18.04 + ROS 1 noetic</li>
<li _msttexthash="17551560" _msthash="241">✅ Ubuntu 20.04 + ROS 1 概念</li>
</ul>
<p dir="auto" _msttexthash="149077149" _msthash="242">正在进行的测试（兼容性工作正在进行中）：</p>
<ul dir="auto">
<li _msttexthash="20236801" _msthash="243">🚧 ROS 2 系列</li>
<li _msttexthash="11155547" _msthash="244">🚧 &gt;= Ubuntu 22.04</li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="25519390" _msthash="245">软件安装 - ROS：</h3><a id="user-content-software-installation---ros" class="anchor" aria-label="永久链接：软件安装 - ROS：" href="#software-installation---ros" _mstaria-label="1063101" _msthash="246"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ol dir="auto">
<li _msttexthash="139087403" _msthash="247">按照 <a href="https://docs.trossenrobotics.com/interbotix_xsarms_docs/" rel="nofollow" _istranslated="1">https://docs.trossenrobotics.com/interbotix_xsarms_docs/</a> 安装 ROS 和 interbotix 软件</li>
<li><font _mstmutation="1" _msttexthash="35805588" _msthash="248">这将创建包含 的目录。</font><code>~/interbotix_ws</code><code>src</code></li>
<li><font _mstmutation="1" _msttexthash="21584355" _msthash="249">git clone 这个仓库</font><code>~/interbotix_ws/src</code></li>
<li><code>source /opt/ros/noetic/setup.sh &amp;&amp; source ~/interbotix_ws/devel/setup.sh</code></li>
<li><code>sudo apt-get install ros-noetic-usb-cam &amp;&amp; sudo apt-get install ros-noetic-cv-bridge</code></li>
<li><font _mstmutation="1" _msttexthash="58026358" _msthash="250">run inside 中，确保构建成功</font><code>catkin_make</code><code>~/interbotix_ws</code></li>
<li><font _mstmutation="1" _msttexthash="280701057" _msthash="251">转到 ，查找函数 。
更改为 .
这可以防止代码在延迟远程操作的每一步都计算 FK。</font><code>~/interbotix_ws/src/interbotix_ros_toolboxes/interbotix_xs_toolbox/interbotix_xs_modules/src/interbotix_xs_modules/arm.py</code><code>publish_positions</code><code>self.T_sb = mr.FKinSpace(self.robot_des.M, self.robot_des.Slist, self.joint_commands)</code><code>self.T_sb = None</code></li>
</ol>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="21539713" _msthash="252">硬件安装：</h3><a id="user-content-hardware-installation" class="anchor" aria-label="永久链接：硬件安装：" href="#hardware-installation" _mstaria-label="907816" _msthash="253"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font _mstmutation="1" _msttexthash="456413711" _msthash="254">本节的目标是运行 ，它启动
与 4 个机器人和 3 个摄像头通信。完成以下步骤后，它应该可以正常工作：</font><code>roslaunch aloha 4arms_teleop.launch</code></p>
<p dir="auto" _msttexthash="352899313" _msthash="255">第 1 步：通过 USB 将 4 个机器人连接到计算机，然后开机。<em _istranslated="1">请勿使用延长线或 USB 集线器</em>。</p>
<ul dir="auto">
<li>
<p dir="auto" _msttexthash="127651563" _msthash="256">要检查机器人是否已连接，<a href="https://emanual.robotis.com/docs/en/software/dynamixel/dynamixel_wizard2/" rel="nofollow" _istranslated="1">请在此处</a>安装 dynamixel 向导</p>
</li>
<li>
<p dir="auto" _msttexthash="3122737358" _msthash="257">Dynamixel 向导是一个非常有用的调试工具，可以连接到机器人的各个电机。它允许
诸如重新启动电机（非常有用）、扭矩开/关和发送命令等操作。
但是，它对机器人的运动学一无所知，因此要小心碰撞。
如果电机扭矩关闭，即关节中没有自动接合的制动器，机器人<em _istranslated="1">就会</em>崩溃。</p>
</li>
<li>
<p dir="auto"><font _mstmutation="1" _msttexthash="97859086" _msthash="258">打开 Dynamixel 向导，进入并选择：</font><code>options</code></p>
<ul dir="auto">
<li _msttexthash="5678283" _msthash="259">协议 2.0</li>
<li _msttexthash="11505897" _msthash="260">所有端口</li>
<li _msttexthash="9769890" _msthash="261">1000000 基点</li>
<li _msttexthash="13297986" _msthash="262">ID 范围从 0 到 10</li>
</ul>
</li>
<li>
<p dir="auto" _msttexthash="81521765" _msthash="263">注意：每次扫描前都重复上述内容。</p>
</li>
<li>
<p dir="auto"><font _mstmutation="1" _msttexthash="150326475" _msthash="264">然后点击 。应该会显示 4 个设备，每个设备有 9 个电机。</font><code>Scan</code></p>
</li>
<li>
<p dir="auto"><font _mstmutation="1" _msttexthash="1367924935" _msthash="265">出现的一个问题是每个机器人绑定到的端口会随着时间的推移而变化，例如机器人
最初可能会突然变为 。为了解决这个问题，我们将每个机器人绑定到一个固定的符号链接
port 的映射如下：</font><code>ttyUSB0</code><code>ttyUSB5</code></p>
<ul dir="auto">
<li><code>ttyDXL_master_right</code><font _mstmutation="1" _msttexthash="163034482" _msthash="266">：右主机器人（主机器人：操作员将持有的机器人）</font></li>
<li><code>ttyDXL_puppet_right</code><font _mstmutation="1" _msttexthash="160676997" _msthash="267">：右 Puppet Robot（Puppet：执行任务的机器人）</font></li>
<li><code>ttyDXL_master_left</code><font _mstmutation="1" _msttexthash="8652137" _msthash="268">： 左 Master Robot</font></li>
<li><code>ttyDXL_puppet_left</code><font _mstmutation="1" _msttexthash="24845938" _msthash="269">： 左木偶机器人</font></li>
</ul>
</li>
<li>
<p dir="auto"><font _mstmutation="1" _msttexthash="45318299" _msthash="270">以 ：right master robot 为例：</font><code>ttyDXL_master_right</code></p>
<ol dir="auto">
<li>
<p dir="auto"><font _mstmutation="1" _msttexthash="122062304" _msthash="271">找到正确的 master robot 当前绑定的端口，例如</font><code>ttyUSB0</code></p>
</li>
<li>
<p dir="auto"><font _mstmutation="1" _msttexthash="161082376" _msthash="272">运行 以获取序列号。使用显示的第一个，格式应类似于 。</font><code>udevadm info --name=/dev/ttyUSB0 --attribute-walk | grep serial</code><code>FT6S4DSP</code></p>
</li>
<li>
<p dir="auto"><code>sudo vim /etc/udev/rules.d/99-fixed-interbotix-udev.rules</code><font _mstmutation="1" _msttexthash="29565939" _msthash="273">并添加以下行：</font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>SUBSYSTEM=="tty", ATTRS{serial}=="&lt;serial number here&gt;", ENV{ID_MM_DEVICE_IGNORE}="1", ATTR{device/latency_timer}="1", SYMLINK+="ttyDXL_master_right"
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="SUBSYSTEM==&quot;tty&quot;, ATTRS{serial}==&quot;<serial number here>&quot;, ENV{ID_MM_DEVICE_IGNORE}=&quot;1&quot;, ATTR{device/latency_timer}=&quot;1&quot;, SYMLINK+=&quot;ttyDXL_master_right&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li>
<p dir="auto"><font _mstmutation="1" _msttexthash="78042978" _msthash="274">这将确保正确的主机器人<em _mstmutation="1" _istranslated="1">始终</em>绑定到</font><code>ttyDXL_master_right</code></p>
</li>
<li>
<p dir="auto" _msttexthash="43289155" _msthash="275">对其余 3 个臂重复此操作。</p>
</li>
</ol>
</li>
<li>
<p dir="auto"><font _mstmutation="1" _msttexthash="46107685" _msthash="276">要应用更改，请运行</font><code>sudo udevadm control --reload &amp;&amp; sudo udevadm trigger</code></p>
</li>
<li>
<p dir="auto"><font _mstmutation="1" _msttexthash="50452649" _msthash="277">如果成功，您应该能够在</font><code>ttyDXL*</code><code>/dev</code></p>
</li>
</ul>
<p dir="auto" _msttexthash="79262001" _msthash="278">第 2 步：设置夹爪电机的最大电流</p>
<ul dir="auto">
<li><font _mstmutation="1" _msttexthash="272525370" _msthash="279">打开 Dynamixel 向导，然后选择人偶手臂的手腕转动器。它的名称应该是</font><code>[ID:009] XM430-W350</code></li>
<li _msttexthash="405615509" _msthash="280">提示：机器人底座上的 LED 在与 Dynamixel Wizard 对话时会闪烁。这将有助于确定选择了哪个机器人。</li>
<li><font _mstmutation="1" _msttexthash="66498952" _msthash="281">查找 ，输入 ，然后点击底部。</font><code>38 Current Limit</code><code>300</code><code>save</code></li>
<li _msttexthash="50528465" _msthash="282">对两个 Puppet Robot 重复此操作。</li>
<li _msttexthash="192729563" _msthash="283">这限制了通过机械手电机的最大电流，以防止过载错误。</li>
</ul>
<p dir="auto" _msttexthash="43853628" _msthash="284">第 3 步：设置 3 台摄像机</p>
<ul dir="auto">
<li>
<p dir="auto" _msttexthash="338056238" _msthash="285">您可以在此处使用 USB 集线器，但<em _istranslated="1">每个集线器最多有 2 个摄像头，以实现合理的延迟</em>。</p>
</li>
<li>
<p dir="auto" _msttexthash="230511658" _msthash="286">为确保所有 3 台相机都绑定到一致的端口，需要执行类似的步骤。</p>
</li>
<li>
<p dir="auto"><font _mstmutation="1" _msttexthash="159831828" _msthash="287">默认情况下，相机会绑定到 ，而我们希望有符号链接</font><code>/dev/video{0, 1, 2...}</code><code>{CAM_RIGHT_WRIST, CAM_LEFT_WRIST, CAM_HIGH}</code></p>
</li>
<li>
<p dir="auto"><font _mstmutation="1" _msttexthash="343460533" _msthash="288">举个例子，假设它现在绑定到 。run 获取它的 serial。使用显示的第一个，格式应类似于 。</font><code>CAM_RIGHT_WRIST</code><code>/dev/video0</code><code>udevadm info --name=/dev/video0 --attribute-walk | grep serial</code><code>0E1A2B2F</code></p>
</li>
<li>
<p dir="auto"><font _mstmutation="1" _msttexthash="22820772" _msthash="289">然后添加以下行</font><code>sudo vim /etc/udev/rules.d/99-fixed-interbotix-udev.rules</code></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>SUBSYSTEM=="video4linux", ATTRS{serial}=="&lt;serial number here&gt;", ATTR{index}=="0", ATTRS{idProduct}=="085c", ATTR{device/latency_timer}="1", SYMLINK+="CAM_RIGHT_WRIST"
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="SUBSYSTEM==&quot;video4linux&quot;, ATTRS{serial}==&quot;<serial number here>&quot;, ATTR{index}==&quot;0&quot;, ATTRS{idProduct}==&quot;085c&quot;, ATTR{device/latency_timer}=&quot;1&quot;, SYMLINK+=&quot;CAM_RIGHT_WRIST&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li>
<p dir="auto"><font _mstmutation="1" _msttexthash="2142595" _msthash="290">对</font><code>{CAM_LEFT_WRIST, CAM_HIGH}</code><code>CAM_RIGHT_WRIST</code></p>
</li>
<li>
<p dir="auto"><font _mstmutation="1" _msttexthash="46107685" _msthash="291">要应用更改，请运行</font><code>sudo udevadm control --reload &amp;&amp; sudo udevadm trigger</code></p>
</li>
<li>
<p dir="auto"><font _mstmutation="1" _msttexthash="50452649" _msthash="292">如果成功，您应该能够在</font><code>{CAM_RIGHT_WRIST, CAM_LEFT_WRIST, CAM_HIGH}</code><code>/dev</code></p>
</li>
</ul>
<p dir="auto" _msttexthash="32392178" _msthash="293">第 4 步：设置 AgileX Tracer 基</p>
<ul dir="auto">
<li _msttexthash="216450416" _msthash="294">通过库存的 CANBUS 转 USB 电缆将底座连接到计算机，然后开机。</li>
<li><font _mstmutation="1" _msttexthash="13056550" _msthash="295">从 AgileX 安装 SDK</font><div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>pip3 install pyagxrobots
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pip3 install pyagxrobots" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li><font _mstmutation="1" _msttexthash="26031668" _msthash="296">启用 gs_usb 内核模块</font><div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>sudo modprobe gs_usb
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="sudo modprobe gs_usb" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li><font _mstmutation="1" _msttexthash="13621647" _msthash="297">启动 CAN 设备</font><div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>sudo ip link set can0 up type can bitrate 500000
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="sudo ip link set can0 up type can bitrate 500000" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li><font _mstmutation="1" _msttexthash="224744104" _msthash="298">如果前面的步骤没有出现错误，您应该能够使用 command 现在看到 can 设备</font><div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>ifconfig -a
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="ifconfig -a" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li><font _mstmutation="1" _msttexthash="57551559" _msthash="299">安装和使用 can-utils 来测试硬件</font><div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>sudo apt install can-utils
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="sudo apt install can-utils" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li><font _mstmutation="1" _msttexthash="20763808" _msthash="300">测试命令：</font><div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code># receiving data from can0
candump can0
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="# receiving data from can0
candump can0" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
</ul>
<p dir="auto" _msttexthash="45057714" _msthash="301">此时，有一个新的终端</p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>conda deactivate # if conda shows up by default
source /opt/ros/noetic/setup.sh &amp;&amp; source ~/interbotix_ws/devel/setup.sh
roslaunch aloha 4arms_teleop.launch
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="conda deactivate # if conda shows up by default
source /opt/ros/noetic/setup.sh &amp;&amp; source ~/interbotix_ws/devel/setup.sh
roslaunch aloha 4arms_teleop.launch" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto" _msttexthash="379975856" _msthash="302">如果未显示错误消息，则计算机应成功连接到所有 3 个摄像头、所有 4 个机器人手臂和机器人底座。</p>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto" _msttexthash="14356329" _msthash="303">故障排除</h4><a id="user-content-trouble-shooting" class="anchor" aria-label="永久链接：故障排除" href="#trouble-shooting" _mstaria-label="650000" _msthash="304"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li _msttexthash="579952074" _msthash="305">确保 Dynamixel Wizard 已断开连接，并且没有应用程序正在使用网络摄像头的流。它将阻止 ROS 连接到
这些设备。</li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="27265004" _msthash="306">软件安装 - Conda：</h3><a id="user-content-software-installation---conda" class="anchor" aria-label="永久链接： 软件安装 - Conda：" href="#software-installation---conda" _mstaria-label="1193725" _msthash="307"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>conda create -n aloha python=3.8.10
conda activate aloha
pip install torchvision
pip install torch
pip install pyquaternion
pip install pyyaml
pip install rospkg
pip install pexpect
pip install mujoco
pip install dm_control
pip install opencv-python
pip install matplotlib
pip install einops
pip install packaging
pip install h5py
pip install tqdm
pip install wandb
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="conda create -n aloha python=3.8.10
conda activate aloha
pip install torchvision
pip install torch
pip install pyquaternion
pip install pyyaml
pip install rospkg
pip install pexpect
pip install mujoco
pip install dm_control
pip install opencv-python
pip install matplotlib
pip install einops
pip install packaging
pip install h5py
pip install tqdm
pip install wandb" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="21498854" _msthash="308">测试远程操作</h3><a id="user-content-testing-teleoperation" class="anchor" aria-label="永久链接：测试远程操作" href="#testing-teleoperation" _mstaria-label="885833" _msthash="309"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="799671665" _msthash="310"><strong _istranslated="1">注意</strong>：在运行以下命令之前，请务必将所有 4 个机器人置于睡眠位置，并打开主机器人的夹持器。
所有机器人都将上升到易于远程操作的高度。</p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code># ROS terminal
conda deactivate
source /opt/ros/noetic/setup.sh &amp;&amp; source ~/interbotix_ws/devel/setup.sh
roslaunch aloha 4arms_teleop.launch

# Right hand terminal
conda activate aloha
cd ~/interbotix_ws/src/aloha/aloha_scripts
python3 one_side_teleop.py right

# Left hand terminal
conda activate aloha
cd ~/interbotix_ws/src/aloha/aloha_scripts
python3 one_side_teleop.py left
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="# ROS terminal
conda deactivate
source /opt/ros/noetic/setup.sh &amp;&amp; source ~/interbotix_ws/devel/setup.sh
roslaunch aloha 4arms_teleop.launch

# Right hand terminal
conda activate aloha
cd ~/interbotix_ws/src/aloha/aloha_scripts
python3 one_side_teleop.py right

# Left hand terminal
conda activate aloha
cd ~/interbotix_ws/src/aloha/aloha_scripts
python3 one_side_teleop.py left" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto" _msttexthash="83133479" _msthash="311">当主侧机械手关闭时，遥控将开始。</p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="12072840" _msthash="312">示例用法</h2><a id="user-content-example-usages" class="anchor" aria-label="永久链接：示例用法" href="#example-usages" _mstaria-label="546949" _msthash="313"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="70100277" _msthash="314">要设置新终端，请运行：</p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>conda activate aloha
cd ~/interbotix_ws/src/aloha/aloha_scripts
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="conda activate aloha
cd ~/interbotix_ws/src/aloha/aloha_scripts" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font _mstmutation="1" _msttexthash="387063586" _msthash="315">我们运行的是用于测试远程操作的，没有数据收集。要收集剧集的数据，请运行：</font><code>one_side_teleop.py</code></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>python3 record_episodes.py --dataset_dir &lt;data save dir&gt; --episode_idx 0
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python3 record_episodes.py --dataset_dir <data save dir> --episode_idx 0" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font _mstmutation="1" _msttexthash="264806607" _msthash="316">这会在 上存储一个 hdf5 文件。
要更改剧集长度和其他参数，请直接编辑。</font><code>&lt;data save dir&gt;</code><code>constants.py</code></p>
<p dir="auto" _msttexthash="94261622" _msthash="317">要可视化收集的剧集，请运行：</p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>python3 visualize_episodes.py --dataset_dir &lt;data save dir&gt; --episode_idx 0
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python3 visualize_episodes.py --dataset_dir <data save dir> --episode_idx 0" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto" _msttexthash="151631805" _msthash="318">要重播使用真实机器人收集的剧集，请运行：</p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>python3 replay_episodes.py --dataset_dir &lt;data save dir&gt; --episode_idx 0
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python3 replay_episodes.py --dataset_dir <data save dir> --episode_idx 0" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto" _msttexthash="146661463" _msthash="319">要在切断电源等之前降低 4 个机器人，请运行：</p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>python3 sleep.py
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python3 sleep.py" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</article></div>
