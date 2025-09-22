---
id: guidelines
name: Guidelines
heading: Guidelines for the Review Process in the Robotics Research Community
div_class: lead
# subheading: Will Catch Your Eye
# image: "http://placehold.it/500x500"
---

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
    <button class="active" onclick="showTab('tab1', this)">Existing Resources</button>
    <button onclick="showTab('tab2', this)">Reviewer Guidelines</button>
  </div>

  <div id="tab1" class="tab-content active">
    <table>
      <thead>
        <tr>
          <th>Resource</th>
          <th>Description</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><a href="https://www.youtube.com/watch?v=W1zPtTt43LI">How to write a good review?</a></td>
          <td>CVPR 2020 Tutorial organized by <a href="https://tsattler.github.io/">Torsten Sattler</a> and <a href="https://dvl.in.tum.de/team/lealtaixe/"> Laura Leal-Taixé </a> </td>
        </tr>
        <tr>
          <td><a href="https://www.youtube.com/watch?v=9Y7NCdKdNyE">Reviewing the review process</a></td>
          <td>ICCV 2021 Tutorial organized by <a href="https://tsattler.github.io/">Torsten Sattler</a> and <a href="https://dvl.in.tum.de/team/lealtaixe/"> Laura Leal-Taixé </a> </td>
        </tr>
        <tr>
          <td><a href="https://github.com/hassony2/useful-computer-vision-phd-resources/blob/master/Awesome-resources-for-better-reviewing-of-computer-vision-papers.md">Awesome resources for better reviewing of computer vision papers</a></td>
          <td>ReadME compiled by <a href="https://hassony2.github.io/">Yana Hasson</a></td>
        </tr>
        <tr>
          <td><a href="https://perceiving-systems.blog/en/news/novelty-in-science">Novelty in Science: A guide for reviewers</a></td>
          <td>Blog by <a href="https://is.mpg.de/ps/person/black">Michael J. Black</a></td>
        </tr>
        <tr>
          <td><a href="https://cvpr2022.thecvf.com/sites/default/files/2021-11/How%20to%20be%20a%20good%20reviewer-tutorials%20for%20cvpr2022%20reviewers.pptx.pdf">How to be a good reviewer?</a></td>
          <td>CVPR 2022 Reviewer Tutorial by the Program Chairs</td>
        </tr>
        <tr>
          <td><a href="https://mvaldenegro.github.io/files/LXCV-CVPR-2021-review-mentoring.pdf">And How to Write Good Reviews</a></td>
          <td>LXCV @ CVPR 2021 Reviewer Mentoring Program by <a href="https://github.com/mvaldenegro">Matias Valdenegro</a></td>
        </tr>
        <tr>
          <td><a href="https://drive.google.com/file/d/1ydN247sEXjnP0P_JByf287ifXNcdoIBM/view">Novelty is in the eye of the beholder</a></td>
          <td>Compiled by <a href="https://prs.igp.ethz.ch/group/people/person-detail.schindler.html">Konrad Schindler</a></td>
        </tr>
        <tr>
          <td><a href="https://www.ieee-ras.org/images/publications/t-ro/HowToReviewAScientificPaper.pdf">How to review a scientific paper:
some guidelines</a></td>
          <td>Presented at IEEE RAS YRP Online Event by <a href="https://team.inria.fr/rainbow/fr/team/prg/">Paolo Robuffo Giordano</a></td>
        </tr>
        <tr>
          <td><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=5663683&tag=1">Surviving the Review Process</a></td>
          <td>Editorial in <a href="https://www.ieee-ras.org/publications/ram">IEEE Robotics & Automation Magazine</a> by <a href="https://faculty.cc.gatech.edu/~seth/">Seth Hutchinson</a></td>
        </tr>
        <tr>
          <td><a href="https://scaron.info/blog/reviewing-a-scientific-paper.html">Reviewing a scientific paper</a></td>
          <td>Blog by <a href="https://scaron.info/">Stéphane Caron</a></td>
        </tr>
        <tr>
          <td><a href="https://natolambert.com/guides/how-to-review-a-paper">How to review a paper</a></td>
          <td>Blog by <a href="https://natolambert.com/">Nathan LAMBERT</a></td>
        </tr>
        <tr>
          <td><a href="https://taliaringer.wordpress.com/2023/08/14/reviewing-papers-with-adhd/">Reviewing Papers with ADHD</a></td>
          <td>Blog by <a href="https://taliaringer.wordpress.com/">Talia Ringer</a></td>
        </tr>
        <tr>
          <td><a href="https://cdn.serc.carleton.edu/files/earth_rendezvous/2015/mini_workshops/mw14/quick_guide_writing_solid.pdf">A Quick Guide to Writing a Solid Peer Review</a></td>
          <td>Published in <a href="https://agupubs.onlinelibrary.wiley.com/journal/23249250">Eos, Transactions American Geophysical Union: Volume 92, Issue 28 </a> by <a href="https://www.kimnicholas.com/">Kimberly Nicholas</a> and W S Gordon </td>
        </tr>
      </tbody>
    </table>
  </div>

  <div id="tab2" class="tab-content">
    <table>
      <thead>
        <tr>
          <th>Resource</th>
          <th>Description</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><a href="https://www.ieee-ras.org/publications/ra-l/ra-l-information-for-reviewers">RA-L Information for Reviewers</a></td>
          <td><a href="https://www.ieee-ras.org/publications/ra-l"> IEEE Robotics and Automation Letters </a></td>
        </tr>
        <tr>
          <td><a href="https://www.ieee-ras.org/conferences-workshops/fully-sponsored/icra/information-for-reviewers">Information for ICRA Reviewers</a></td>
          <td><a href="https://www.ieee-ras.org/conferences-workshops/fully-sponsored/icra"> IEEE International Conference on Robotics and Automation (ICRA) 2026 </a></td>
        </tr>
        <tr>
          <td><a href="https://cvpr.thecvf.com/Conferences/2024/ReviewerGuidelines">CVPR 2024 Reviewer Guidelines</a></td>
          <td><a href="https://cvpr.thecvf.com/Conferences/2024">  IEEE / CVF Computer Vision and Pattern Recognition Conference (CVPR) 2024 </a></td>
        </tr>
        <tr>
          <td><a href="https://neurips.cc/Conferences/2023/ReviewerGuidelines">2023 Reviewer Guidelines</a></td>
          <td><a href="https://neurips.cc/Conferences/2023">  The Thirty-Seventh Annual Conference on Neural Information Processing Systems (NeurIPS) 2023 </a></td>
        </tr>
        <tr>
          <td><a href="https://icml.cc/Conferences/2022/ReviewerTutorial">Reviewer Tutorial</a></td>
          <td><a href="https://neurips.cc/Conferences/2023">  The Thirty-Ninth International Conference on Machine Learning (ICML) 2022 </a></td>
        </tr>
      </tbody>
    </table>
  </div>
</div>

<script>
  function showTab(tabId, button) {
    document.querySelectorAll('.tab-content').forEach(el => el.classList.remove('active'));
    document.getElementById(tabId).classList.add('active');
    document.querySelectorAll('.tab-buttons button').forEach(btn => btn.classList.remove('active'));
    button.classList.add('active');
  }
</script>
