# Hello there 👋

<!-- ![visitors](https://visitor-badge.laobi.icu/badge?page_id=zhenye-na.zhenye-na) -->
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=102)](https://github.com/ellerbrock/open-source-badge/)


```typescript
type Experience = {
  framework: string,
  rate: number,
};

class SoftwareEngineer {
  private _role: string;
  private _experience: Experience[]; 
  private _languages: string[];
  
  contructor() {
    this._role = 'Software Engineer'
    this._experience = [
      { framework: 'ExpressJS', rate: 5 },
      { framework: 'NestJS', rate: 5 },
      { framework: 'React', rate: 5 },
      { framework: 'Vue', rate: 4.5 },
      { framework: 'Typescript', rate: 4.5 },
    ];
    
    this._languages = [
      'Javscript',
      'Typescript',
    ];
  }
  
  get yearsOfExp () {
    return moment().diff('2010-10-01', 'years');
  }
}
```
