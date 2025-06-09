# Review-With-Me
LINK: https://www.review-with-me.com

IAAS Website for sharing and reviewing various movies, anime and video games.

#Whats been used:
  - Ubuntu
  - Apache
  - HTML5
  - GitHub

#HTML Code for Tabs:
##  <!-- Navigation Bar -->
      <nav>
        <a href="#" onclick="showTab('home')">Home</a>
        <a href="#" onclick="showTab('create')">Create Account</a>
        <a href="#" onclick="showTab('about')">About</a>
    <a href="#" onclick="showTab('Copyright')">Copyright</a>
      </nav>
    
      <!-- Home Tab -->
      <div id="home" class="tab-content active">
        <h1>Welcome to Review With Me!</h1>
        <h2>Movies. Anime. Games.</h2>
        <button class="btn" onclick="alert('This is a university project for student 34430879.')">Click Me</button>
      </div>
    
      <!-- Create Account Tab -->
      <div id="create" class="tab-content">
        <h1>Create an Account</h1>
        <form>
          <input type="text" placeholder="Username" required>
          <input type="email" placeholder="Email Address" required>
          <input type="password" placeholder="Password" required>
          <input type="submit" value="Sign Up">
        </form>
      </div>
    
      <!-- About Tab -->
      <div id="about" class="tab-content">
        <h1>About Review With Me</h1>
              <p>A platform where fans of movies, anime, and games can share reviews, connect, and build communities together.</p>
          <p>The goal of this webpage is for users to review various forms of media such as movies, video games, anime, manga, etc.
                 Users can then share their reviews and join communities with like-minded individuals. Users will have access to a fully
                 customisable profile, to which they can 'show off' their favourite pieces of media, allowing them to form real connections with others.In an easier sense; this website will be like MyAnimeList and Lett>  </div>
          
          <!-- Copyright Tab -->
          <div id="Copyright" class="tab-content">
            <p>Permission is hereby granted, free of charge, to any person obtaining a copy
          of this software and associated documentation files (the "Software"), to deal
          in the Software without restriction, including without limitation the rights
          to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
          copies of the Software, and to permit persons to whom the Software is
          furnished to do so, subject to the following conditions:
          
          <p>The above copyright notice and this permission notice shall be included in all
          copies or substantial portions of the Software.</p>
          
          <p>THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
          IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
          FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
          AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
          LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
          OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
          SOFTWARE.</p>
          
          
          
            <!-- Tab Switch Script -->
            <script>
              function showTab(tabId) {
                const tabs = document.querySelectorAll('.tab-content');
                tabs.forEach(tab => tab.classList.remove('active'));
          
                document.getElementById(tabId).classList.add('active');
              }
            </script>
          
          </body>
          </html>"
