# AngularNgContent

Projenin [Angular CLI](https://github.com/angular/angular-cli) version 14.1.1.

## Development server

Terminalden `ng serve` dendikten sonra  `http://localhost:4200/`. adresinden uygulamanın çalışma anına geçilebilir

## ng-content
html içeriklerini parent component’ten child component’e geçirmemizi ve render etmemizi sağlar

## Parent Component üzerinden Child componente gönderilmek istenilen Html içerik
 ```
   <app-detail>
   <p birinci>içerik</p>
   </app-detail>

 ```
 
 ## Child Component içerisinde Parent component den gönderilen içeriğin yakalandığı kısım
 ```
  <ng-content select="[birinci]"></ng-content>
 ```
  