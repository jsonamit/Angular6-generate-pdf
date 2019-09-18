# Install these thing.

npm install jspdf  
npm install html2canvas  

# When we are done with the installation part, it's time to import it into our component using the import statement.

import * as jspdf from 'jspdf';  
  
import html2canvas from 'html2canvas';  

# Install Angular Material, Angular CDK and add in app module.

npm install --save @angular/material @angular/cdk

import { MatCardModule } from '@angular/material/card';

@NgModule({ ..
 imports: [..
MatCardModule]


