style{
.profile-container {
  max-width: 800px;
  margin: 40px auto;
  padding: 20px;
  background-color: #f9f9f9;
  border: 1px solid #ddd;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.profile-header {
  text-align: center;
  margin-bottom: 20px;
}

.profile-header h1 {
  font-size: 36px;
  font-weight: bold;
  color: #333;
}

.profile-stats {
  display: flex;
  justify-content: space-between;
  margin-bottom: 20px;
}

.stat {
  text-align: center;
  margin: 0 20px;
}

.stat h2 {
  font-size: 24px;
  font-weight: bold;
  color: #333;
}

.stat p {
  font-size: 16px;
  color: #666;
}

.profile-bio {
  margin-bottom: 20px;
}

.profile-skills {
  margin-bottom: 20px;
}

.profile-skills h2 {
  font-size: 24px;
  font-weight: bold;
  color: #333;
  margin-bottom: 10px;
}

.profile-skills ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

.profile-skills li {
  display: inline-block;
  margin-right: 10px;
  padding: 5px 10px;
  background-color: #f0f0f0;
  border: 1px solid #ddd;
  border-radius: 5px;
  font-size: 16px;
  color: #666;
}


}
<div class="profile-container">
  <div class="profile-header">
    <h1>Nama Anda</h1>
    <p>Deskripsi singkat tentang Anda</p>
  </div>
  <div class="profile-stats">
    <div class="stat">
      <h2>100</h2>
      <p>Followers</p>
    </div>
    <div class="stat">
      <h2>50</h2>
      <p>Repositories</p>
    </div>
    <div class="stat">
      <h2>200</h2>
      <p>Contributions</p>
    </div>
  </div>
  <div class="profile-bio">
    <p>Tentang Anda...</p>
  </div>
  <div class="profile-skills">
    <h2>Skills</h2>
    <ul>
      <li>HTML</li>
      <li>CSS</li>
      <li>JavaScript</li>
      <li>Python</li>
    </ul>
  </div>
</div>
