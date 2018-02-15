### Who has seen disabled tests?

```cs
[TestMethod]
[Ignore]
public void Status_WithId34_ShouldFindItemWithId34()
{
    // Act
    var viewResult = _sut.Status(34) as ViewResult;
```
    
```js
it('should have saved file', () => {
    sut.save('a file');
    // expect(TempFolder.writeFile).to.have.been.called;
});
```