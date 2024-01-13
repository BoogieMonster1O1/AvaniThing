<script>
    let imageUrls = [
      '1.png',
      '2.png',
      '3.png',
      '4.png',
      '5.png',
      '6.png',
      '7.png',
      '8.png',
      '9.png',
      '10.png',
      '11.png',
      '12.png'
    ];
</script>

<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4 p-4" id="info">
    <!-- Professor Information -->
    <div class="dark:bg-gray-800 bg-gray-400 rounded p-4">
      <h2 class="text-2xl font-semibold mb-2">Professor and Associate Dean</h2>
      <p><span class="font-semibold">Qualification:</span> PhD</p>
      <p><span class="font-semibold">Experience:</span> 30 years in teaching, 1 year in industry, 19+ years in research</p>
      <p><span class="font-semibold">Area of Interest:</span> Computer Networks & Management, Multimedia Communications, Computer Architecture, Protocol Design</p>
      <p><span class="font-semibold">Date of Joining RVCE:</span> 08/12/2005</p>
      <p><span class="font-semibold">Email:</span> nagarajags@rvce.edu.in</p>
    </div>
  
    <!-- Project Guided -->
    <div class="dark:bg-gray-800 bg-gray-400 rounded p-4">
      <h2 class="text-2xl font-semibold mb-2">Project Guided</h2>
      <p><span class="font-semibold">UG Projects Guided:</span> 50+</p>
      <p><span class="font-semibold">PG Projects Guided:</span> 50+</p>
      <p><span class="font-semibold">Doctorate Students:</span> Completed: 08, Guiding: 06</p>
    </div>
  
    <!-- Publications -->
    <div class="dark:bg-gray-800 bg-gray-400 rounded p-4">
      <h2 class="text-2xl font-semibold mb-2">Publications</h2>
      <p><span class="font-semibold">National Journals:</span> 01</p>
      <p><span class="font-semibold">National Conferences:</span> 17</p>
      <p><span class="font-semibold">International Journals:</span> 66</p>
      <p><span class="font-semibold">International Conferences:</span> 45</p>
      <p><span class="font-semibold">Book Chapters Published:</span> 07</p>
      <p><span class="font-semibold">Patent Granted:</span> 01</p>
    </div>
  </div>

  <div class="container mx-auto mt-8">
    <!-- Academic Qualifications -->
    <div class="mb-6">
      <h2 class="text-4xl font-bold mb-2">Academic Qualifications</h2>
      <ul class="list-disc flex flex-col pl-8">
        <li>Doctor of Philosophy (Ph.D.) in Computer Science and Engineering from Dr MGR University, Chennai, India, 2011.</li>
        <li>Master of Engineering (M.E. Master of Engineering Management from, Mysore University, India, 1996.</li>
        <li>Bachelor of Engineering (B.E.) in Computer Science and Engineering, Bangalore University, India, 1991.</li>
        <li>CCCNA Certified instructor from RVCE CISCO academy-2012.</li>
      </ul>
    </div>
  
    <!-- Work Experience -->
    <div class="mb-6">
      <h2 class="text-2xl font-bold mb-2">Work Experience</h2>
      <p>30+ Years of Teaching Experience, 19+ Years of Research Experience, 6+ Years of Skill development experience in CCNA for UG / PG Students, Intel FPGA and SoC’s instructor.</p>
    </div>
  
    <!-- Positions Held -->
    <div>
      <h2 class="text-2xl font-bold mb-2">Positions Held</h2>
      <ul class="list-disc flex flex-col pl-8">
        <li>Lecturer, Assistant Professor, Associate Professor, Professor, Associate Dean in Dept. of Computer Science Engineering, RVCE, Bangalore</li>
      </ul>
    </div>
  </div>

  <div id="contact" class="container mx-auto mt-8">
    <h2 class="text-4xl font-bold mb-2">Contact Information</h2>
  
    <!-- Phone Numbers -->
    <div class="mb-4">
      <p>Phone No:</p>
      <ul class="list-disc pl-8">
        <li>9880017459</li>
        <li>080-67188204 (Dept-Office)</li>
      </ul>
    </div>
  
    <!-- Email -->
    <div>
      <p>Email:</p>
      <p class="pl-8">nagarajags@rvce.edu.in</p>
    </div>
  </div>
  
  <div class="container mx-auto m-8">
    <h2 class="text-4xl font-bold mb-4" id="gallery">Gallery</h2>
  
    <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-4 p-8 pt-0">
      {#each imageUrls as imageUrl (imageUrl)}
        <img src={imageUrl} alt="image hehe" class="w-full h-full object-cover rounded-lg" />
      {/each}
    </div>
  </div>
