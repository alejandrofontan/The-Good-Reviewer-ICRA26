---
id: guidelines
name: Guidelines
heading: Guidelines for the Review Process in the Robotics Research Community
div_class: lead
# subheading: Will Catch Your Eye
# image: "http://placehold.it/500x500"
---

A curated list of resources to help unify and standardize the landscape of Visual SLAM, Structure-from-Motion, datasets, tools, and educational content. This page collects links to key projects, foundational papers, tools, and talks.

🔗 Find the most up-to-date list here: [Unifying Visual SLAM GitHub Repository](https://github.com/VSLAM-LAB/Unifying-Visual-SLAM)

👋 Contributions are welcome! Feel free to open an issue or submit a pull request to suggest more tools, papers, or resources.

<style>
  .tab-buttons {
    display: flex;
    flex-wrap: wrap;
    border-bottom: 2px solid #ccc;
    margin-bottom: 1rem;
  }

  .tab-buttons button {
    background: none;
    border: none;
    border-bottom: 3px solid transparent;
    padding: 10px 16px;
    cursor: pointer;
    font-size: 2rem;
    transition: border-color 0.3s, background-color 0.3s;
  }

  .tab-buttons button:hover {
    background-color: #f0f0f0;
  }

  .tab-buttons button.active {
    border-bottom: 3px solid #007bff;
    font-weight: bold;
    color: #007bff;
  }

  .tab-content {
    display: none;
  }

  .tab-content.active {
    display: block;
  }

  table {
    width: 100%;
    border-collapse: collapse;
    margin-bottom: 1rem;
  }

  th, td {
    padding: 8px;
    border: 1px solid #ddd;
    text-align: left;
  }

  th {
    background-color: #f7f7f7;
  }
</style>

<div>
  <div class="tab-buttons">
    <button class="active" onclick="showTab('tab1', this)">VSLAM</button>
    <button onclick="showTab('tab8', this)">SfM</button>
    <button onclick="showTab('tab3', this)">Benchmark</button>
    <button onclick="showTab('tab4', this)">Datasets</button>
    <button onclick="showTab('tab2', this)">Education</button>
    <button onclick="showTab('tab5', this)">Foundational</button>
    <button onclick="showTab('tab6', this)">Talks</button>
    <button onclick="showTab('tab9', this)">Tools</button>
    <button onclick="showTab('tab7', this)">More</button>
  </div>

  <div id="tab1" class="tab-content active">
    <table>
      <thead><tr><th></th><th>Existing resources:</th></tr></thead>
      <tbody>
        <tr><td><a href="https://www.youtube.com/watch?v=W1zPtTt43LI">How to write good reviews</a></td><td>How to write good reviews</td></tr>
        <tr><td><a href="https://github.com/hassony2/useful-computer-vision-phd-resources/blob/master/Awesome-resources-for-better-reviewing-of-computer-vision-papers.md">Awesome-resources-for-better-reviewing-of-computer-vision-papers.md </a></td><td>Awesome-resources-for-better-reviewing-of-computer-vision-papers.md </td></tr>
      </tbody>
    </table>
  </div>

  <div id="tab2" class="tab-content">
    <table>
      <thead><tr><th></th><th>New Resources</th></tr></thead>
      <tbody>
        <tr><td>Mentorship program at RAS</td><td>Mentorship program at RAS</td></tr>
      </tbody>
    </table>
  </div>
<script>
  function showTab(tabId, button) {
    document.querySelectorAll('.tab-content').forEach(el => el.classList.remove('active'));
    document.getElementById(tabId).classList.add('active');
    document.querySelectorAll('.tab-buttons button').forEach(btn => btn.classList.remove('active'));
    button.classList.add('active');
  }
</script>
