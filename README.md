<!DOCTYPE html>
<html lang="zh-CN">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>智能门窗销售考试</title>
<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Microsoft YaHei", Arial, sans-serif;
}
body {
  background-color: #f7f8fa;
  padding: 20px;
}
.container {
  max-width: 920px;
  margin: 0 auto;
  background: #fff;
  border-radius: 16px;
  padding: 40px 32px;
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.06);
}
.header {
  text-align: center;
  margin-bottom: 30px;
}
.header h1 {
  font-size: 26px;
  color: #1f2937;
  margin-bottom: 8px;
}
.header p {
  color: #6b7280;
  font-size: 15px;
}
.user-info {
  background: #f9fafb;
  padding: 18px 24px;
  border-radius: 12px;
  margin-bottom: 32px;
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 12px;
}
.user-info label {
  font-size: 16px;
  color: #374151;
  font-weight: 500;
}
.user-info input {
  padding: 12px 16px;
  width: 280px;
  border: 1px solid #d1d5db;
  border-radius: 8px;
  font-size: 15px;
  outline: none;
  transition: border 0.2s;
}
.user-info input:focus {
  border-color: #2563eb;
}
.section {
  margin-bottom: 36px;
}
.section-title {
  font-size: 18px;
  color: #1f2937;
  background: #eff6ff;
  padding: 12px 18px;
  border-left: 5px solid #2563eb;
  border-radius: 8px;
  margin-bottom: 20px;
  font-weight: 600;
}
.question {
  margin-bottom: 22px;
}
.question p {
  font-size: 15px;
  color: #1f2937;
  margin-bottom: 10px;
  line-height: 1.5;
}
.answer {
  width: 100%;
  height: 80px;
  padding: 14px 16px;
  border: 1px solid #d1d5db;
  border-radius: 10px;
  font-size: 15px;
  resize: vertical;
  outline: none;
  transition: border 0.2s;
}
.answer:focus {
  border-color: #2563eb;
}
.submit-box {
  text-align: center;
  margin-top: 40px;
}
#submitBtn {
  background-color: #2563eb;
  color: #fff;
  border: none;
  padding: 14px 40px;
  border-radius: 10px;
  font-size: 16px;
  font-weight: 500;
  cursor: pointer;
  transition: background 0.2s;
}
#submitBtn:hover {
  background-color: #1d4ed8;
}
</style>
</head>

<body>
<div class="container">
  <div class="header">
    <h1>智能门窗销售考试</h1>
    <p>请认真填写，完成后点击提交，试卷将自动发送至管理员</p>
  </div>

  <div class="user-info">
    <label>姓名：</label>
    <input type="text" id="username" placeholder="请输入您的姓名">
  </div>

  <!-- 前装产品 -->
  <div class="section">
    <div class="section-title">一、前装产品基础类</div>

    <div class="question"><p>1. 全景门配套材料有哪些？品牌、系列？</p><textarea class="answer" data-title="1. 全景门配套材料有哪些？品牌、系列？"></textarea></div>
    <div class="question"><p>2. 重型门配套材料有哪些？品牌、系列？</p><textarea class="answer" data-title="2. 重型门配套材料有哪些？品牌、系列？"></textarea></div>
    <div class="question"><p>3. 极简门配套材料有哪些？品牌、系列？</p><textarea class="answer" data-title="3. 极简门配套材料有哪些？品牌、系列？"></textarea></div>
    <div class="question"><p>4. 完美系统材料有哪些？品牌、系列？</p><textarea class="answer" data-title="4. 完美系统材料有哪些？品牌、系列？"></textarea></div>
    <div class="question"><p>5. 平开窗适配材料有哪些？品牌、系列？</p><textarea class="answer" data-title="5. 平开窗适配材料有哪些？品牌、系列？"></textarea></div>
    <div class="question"><p>6. 隐藏式平开电机是有刷还是无刷？结构、算法、特点？</p><textarea class="answer" data-title="6. 隐藏式平开电机是有刷还是无刷？结构、算法、特点？"></textarea></div>
    <div class="question"><p>7. 隐藏式平开电机有几种？</p><textarea class="answer" data-title="7. 隐藏式平开电机有几种？"></textarea></div>
    <div class="question"><p>8. 直驱推拉电机结构、算法、特点？</p><textarea class="answer" data-title="8. 直驱推拉电机结构、算法、特点？"></textarea></div>
    <div class="question"><p>9. 直驱推拉电机有几款型号？</p><textarea class="answer" data-title="9. 直驱推拉电机有几款型号？"></textarea></div>
    <div class="question"><p>10. 智能锁有哪些？</p><textarea class="answer" data-title="10. 智能锁有哪些？"></textarea></div>
    <div class="question"><p>11. 锁要不要接线？</p><textarea class="answer" data-title="11. 锁要不要接线？"></textarea></div>
    <div class="question"><p>12. 锁具跟其它指纹锁具有什么区别？</p><textarea class="answer" data-title="12. 锁具跟其它指纹锁具有什么区别？"></textarea></div>
    <div class="question"><p>13. 直驱电机一共有几个尺寸？</p><textarea class="answer" data-title="13. 直驱电机一共有几个尺寸？"></textarea></div>
    <div class="question"><p>14. 控制器有几款？</p><textarea class="answer" data-title="14. 控制器有几款？"></textarea></div>
    <div class="question"><p>15. APP有哪几款？</p><textarea class="answer" data-title="15. APP有哪几款？"></textarea></div>
  </div>

  <!-- 后装产品 -->
  <div class="section">
    <div class="section-title">二、后装产品基础类</div>

    <div class="question"><p>1. 后装产品都有哪些？</p><textarea class="answer" data-title="1. 后装产品都有哪些？"></textarea></div>
    <div class="question"><p>2. 能装在哪些窗户上？</p><textarea class="answer" data-title="2. 能装在哪些窗户上？"></textarea></div>
    <div class="question"><p>3. 安装对窗户有什么要求？</p><textarea class="answer" data-title="3. 安装对窗户有什么要求？"></textarea></div>
    <div class="question"><p>4. 有哪些功能？</p><textarea class="answer" data-title="4. 有哪些功能？"></textarea></div>
    <div class="question"><p>5. 跟其它同类产品有什么区别？</p><textarea class="answer" data-title="5. 跟其它同类产品有什么区别？"></textarea></div>
  </div>

  <!-- 客户问题 -->
  <div class="section">
    <div class="section-title">三、客户常见问题类</div>

    <div class="question"><p>1. 你们公司干这个多久了？</p><textarea class="answer" data-title="1. 你们公司干这个多久了？"></textarea></div>
    <div class="question"><p>2. 你们公司在哪里？</p><textarea class="answer" data-title="2. 你们公司在哪里？"></textarea></div>
    <div class="question"><p>3. 产品可以做哪些门/窗类型？</p><textarea class="answer" data-title="3. 产品可以做哪些门/窗类型？"></textarea></div>
    <div class="question"><p>4. 我想开模怎么办？</p><textarea class="answer" data-title="4. 我想开模怎么办？"></textarea></div>
    <div class="question"><p>5. 我不想开模怎么办？</p><textarea class="answer" data-title="5. 我不想开模怎么办？"></textarea></div>
    <div class="question"><p>6. 有哪些企业用你们产品？</p><textarea class="answer" data-title="6. 有哪些企业用你们产品？"></textarea></div>
    <div class="question"><p>7. 电机质保多久？</p><textarea class="answer" data-title="7. 电机质保多久？"></textarea></div>
    <div class="question"><p>8. 锁具质保多久？</p><textarea class="answer" data-title="8. 锁具质保多久？"></textarea></div>
    <div class="question"><p>9. 控制器质保多久？</p><textarea class="answer" data-title="9. 控制器质保多久？"></textarea></div>
    <div class="question"><p>10. 皮带质保多久？</p><textarea class="answer" data-title="10. 皮带质保多久？"></textarea></div>
    <div class="question"><p>11. 不符合质保范围（人为或超出年限）怎么处理？</p><textarea class="answer" data-title="11. 不符合质保范围（人为或超出年限）怎么处理？"></textarea></div>
    <div class="question"><p>12. 客户说价格太贵怎么回应？</p><textarea class="answer" data-title="12. 客户说价格太贵怎么回应？"></textarea></div>
    <div class="question"><p>13. 售后是你们做还是我们做？</p><textarea class="answer" data-title="13. 售后是你们做还是我们做？"></textarea></div>
    <div class="question"><p>14. 控制器只有一款吗？</p><textarea class="answer" data-title="14. 控制器只有一款吗？"></textarea></div>
    <div class="question"><p>15. 可以连接哪些智能家居？</p><textarea class="answer" data-title="15. 可以连接哪些智能家居？"></textarea></div>
    <div class="question"><p>16. 产品有哪些功能？</p><textarea class="answer" data-title="16. 产品有哪些功能？"></textarea></div>
  </div>

  <div class="submit-box">
    <button id="submitBtn">提交试卷</button>
  </div>
</div>

<script>
// 获取设备信息
function getDevice() {
  const ua = navigator.userAgent;
  let dev = "未知设备";
  if (ua.match(/iPhone|iPad|iPod/)) dev = "苹果iOS设备";
  else if (ua.match(/Android/)) dev = "Android设备";
  else if (ua.match(/Windows/)) dev = "Windows电脑";
  else if (ua.match(/Mac/)) dev = "Mac电脑";
  return dev + " | " + ua;
}

// 获取IP
async function getIp() {
  try {
    let r = await fetch("https://api.ipify.org?format=json");
    let j = await r.json();
    return j.ip;
  } catch (e) {
    return "获取失败";
  }
}

// 提交
document.getElementById("submitBtn").onclick = async function () {
  let name = document.getElementById("username").value.trim();
  if (!name) {
    alert("请填写姓名！");
    return;
  }

  let ip = await getIp();
  let device = getDevice();

  let txt = "📄 智能门窗销售考试答卷\n";
  txt += "========================================\n";
  txt += "👤 姓名：" + name + "\n";
  txt += "🌐 IP地址：" + ip + "\n";
  txt += "📱 设备信息：" + device + "\n";
  txt += "========================================\n\n";

  document.querySelectorAll(".answer").forEach((item) => {
    let title = item.getAttribute("data-title");
    let ans = item.value.trim() || "【未作答】";
    txt += title + "\n▶ 答案：" + ans + "\n\n";
  });

  // 发送到你的邮箱
  let mail = "1014520213@qq.com";
  let sub = encodeURIComponent("【考试提交】" + name);
  let bod = encodeURIComponent(txt);
  window.location.href = "mailto:" + mail + "?subject=" + sub + "&body=" + bod;

  alert("提交成功！试卷已发送至管理员邮箱");
};
</script>
</body>
</html>
