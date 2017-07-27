# icondropdown
JavaScript Library that will add a user designated image, then add a drop down menu to the image. 

Example:
   var menuArray = [    
      ['Dashboard', '/dashboard/'],    
      ['User Accounts', '/admin/SitePages/AccountCheck.aspx'],    
      ['Submitted Hours', '/admin/SitePages/UserPerformanceCheck.aspx']   
   ];      
   
   IconDropDown.init({    
      element: 'adminDD',    
      iconLink: '/dashboard/SiteAssets/TaskPerf/menuIcon.png',   
      iconWidth: 60, 
      linkArray: menuArray,    
      arrowOffSet: -60 
  });
  
  
  element - is the HTML element ID that this icon menu will bed added to
  iconLink - href to the image that you wish to use as an icon
  iconWidth - how wide you want the image to be
  linkArray - an 2D array that stores the name of the link and URL
  arrowOffSet - allows you to move the dropdown to align better with your image
