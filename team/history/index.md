---
title: 历史团队成员   
---

<div class="team-links" align="center">

  <!-- 所有队员 -->
  <a class="team-card all-members" href="{{ '/team/all' | relative_url }}">
    <i class="fa-solid fa-users"></i>
    <span>所有队员</span>
  </a>

  <!-- 本赛季 -->
  <a class="team-card season" href="{{ '/team' | relative_url }}">
    <i class="fa-solid fa-user-group"></i>
    <span>本赛季团队成员</span>
  </a>

  <!-- 25赛季 -->
  <a class="team-card season" href="{{ '/team' | relative_url }}">
    <i class="fa-solid fa-user-group"></i>
    <span>25赛季团队成员</span>
  </a>

  <!-- 24赛季 -->
  <a class="team-card season" href="{{ '/team/24-season' | relative_url }}">
    <i class="fa-solid fa-user-group"></i>
    <span>24赛季团队成员</span>
  </a>

  <!-- 23赛季 -->
  <a class="team-card season" href="{{ '/team/23-season' | relative_url }}">
    <i class="fa-solid fa-user-group"></i>
    <span>23赛季团队成员</span>
  </a>

  <!-- 22赛季 -->
  <!-- <a class="team-card season" href="{{ '/team/22-season' | relative_url }}">
    <i class="fa-solid fa-user-group"></i>
    <span>22赛季团队成员</span>
  </a> -->

</div>

<style>
.team-links {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 1.2rem;
  margin-top: 1.5rem;
}

.team-card {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-decoration: none;
  border-radius: 12px;
  padding: 1rem 1.5rem;
  width: 180px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.1);
  transition: all 0.2s ease;
  font-size: 1.05rem;
  font-weight: 600;
}

/* 所有队员 - 突出显示 */
.team-card.all-members {
  background: #007bff;
  color: white;
}
.team-card.all-members i {
  color: white;
}
.team-card.all-members:hover {
  background: #0056b3;
}

/* 各赛季卡片 - 统一样式 */
.team-card.season {
  background: #f9f9f9;
  color: #333;
}
.team-card.season i {
  color: #007bff;
}
.team-card.season:hover {
  background: #f0f7ff;
  box-shadow: 0 4px 12px rgba(0,0,0,0.15);
  transform: translateY(-3px);
}

.team-card i {
  font-size: 1.8rem;
  margin-bottom: 0.5rem;
}
</style>
