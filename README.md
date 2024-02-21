# React
test file
https://www.tutorialspoint.com/angular_material7/angular_material7_sidenav.htm


.tp-container {
   position: absolute;
   top: 0;
   bottom: 0;
   left: 0;
   right: 0;
   background: #eee;
}
.tp-section {
   display: flex;
   align-content: center;
   align-items: center;
   height: 60px;
   width:100px;   
}

<mat-sidenav-container class = "tp-container">
   <mat-sidenav mode = "side" opened>
      <section class = "tp-section">
         <span>File</span>
      </section>
      <section class = "tp-section">
         <span>Edit</span>
      </section>
   </mat-sidenav>
   <mat-sidenav-content>Main content</mat-sidenav-content>
</mat-sidenav-container>

