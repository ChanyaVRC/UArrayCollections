# UList 
List�̋@�\��񋟂���N���X�ł��B  
������`array`�ɂ�List�Ƃ��ĉ^�p����z��ϐ���ݒ肵�Ă��������B

## ���상�\�b�h

### UList.Initialize(ref T[] `array`)
�z��`array`�����������A�v�f���[���̔z��Ƃ���B

### UList.Add<T>(ref T[] `array`, T `value`)
�z��`array`�̖����ɗv�f`value`��ǉ�����B

### UList.AddRange<T>(ref T[] `array`, T[] `values`)
�z��`array`�̖����ɕʂ̔z��`values`�̗v�f��ǉ�����B

### UList.Insert<T>(ref T[] `array`, int `index`, T `value`)
�z��`array`��`index`�̈ʒu�ɗv�f`value`��}������B
- �K�v�����F`index`��0�ȏ�A�����v�f���ȉ�

### UList.InsertRange<T>(ref T[] `array`, int `index`, T[] `values`)
�z��`array`��`index`�̈ʒu�ɕʂ̔z��`values`�̗v�f��}������B
- �K�v�����F`index`��0�ȏ�A�����v�f������

### UList.RemoveAt<T>(ref T[] `array`, int `index`)
�z��`array`��`index`�̈ʒu�̗v�f���폜����B�z��̗v�f���͂��̕���������B
- �K�v�����F`index`��0�ȏ�A�����v�f������

### UList.Remove<T>(ref T[] `array`, T `value`)
�z��`array`���������A`value`�Ɉ�v����ŏ��̗v�f���폜����B�z��̗v�f���͂��̕���������B

### UList.RemoveAll<T>(ref T[] `array`, T `value`)
�z��`array`���������A`value`�Ɉ�v����S�Ă̗v�f���폜����B�z��̗v�f���͂��̕���������B

### UList.RemoveRange<T>(ref T[] `array`, int `index`, int `count`)
�z��`array`��`index`�̈ʒu����`count`���̗v�f���폜����B�z��̗v�f���͂��̕���������B
- �K�v�����@�F`index`��0�ȏ�A�����v�f������
- �K�v�����A�F`count`��0�ȏ�

### UList.Resize<T>(ref T[] `array`, int `length`)
�z��`array`�̗v�f����`length`�ɂ���B
- �K�v�����F`length`��0�ȏ�

### UList.Reverse<T>(ref T[] `array`)
�z��`array`�̗v�f�𔽓]������B

## �擾���\�b�h

### int UList.IndexOf<T>(T[] `array`, T `value`)
�z��`array`���������A`value`�Ɉ�v����ŏ��̗v�f�̃C���f�b�N�X�ԍ���Ԃ��B��v����v�f���Ȃ��ꍇ��-1��Ԃ��B

### int UList.IndexOf<T>(T[] `array`, T `value`, int `start`)
�z��`array`��`start`�̈ʒu���猟�����A`value`�Ɉ�v����ŏ��̗v�f�̃C���f�b�N�X�ԍ���Ԃ��B��v����v�f���Ȃ��ꍇ��-1��Ԃ��B

### int UList.LastIndexOf<T>(T[] `array`, T `value`)
�z��`array`������������A`value`�Ɉ�v����ŏ��̗v�f�̃C���f�b�N�X�ԍ���Ԃ��B��v����v�f���Ȃ��ꍇ��-1��Ԃ��B

### int UList.LastIndexOf<T>(T[] `array`, T `value`, int `start`)
�z��`array`��`start`�̈ʒu�������������A`value`�Ɉ�v����ŏ��̗v�f�̃C���f�b�N�X�ԍ���Ԃ��B��v����v�f���Ȃ��ꍇ��-1��Ԃ��B

### bool UList.Contains<T>(T[] array, T value)
�z��`array`��`value`�̗v�f���܂�ł����`true`�A�܂�ł��Ȃ����`false`��Ԃ��B

### T[] GetRange<T>(T[] `array`, int `index`, int `count`)
�z��`array`��`index`�̈ʒu����`count`���̗v�f���擾����B
- �K�v�����@�F`index`��0�ȏ�A�����v�f������
- �K�v�����A�F`count`��0�ȏ�


# UDict 
Dictionary�̋@�\��񋟂���N���X�ł��B  
������`key`��`value`�ɂ�Dictionary�Ƃ��ĉ^�p����z��ϐ���ݒ肵�Ă��������B  
`key`��`value`�͓����C���f�b�N�X�ԍ��ő΂ƂȂ�A�v�f���͕K����v������K�v������܂��B  

## ���상�\�b�h

### UDict.Initialize<TKey, TValue>(ref TKey[] `keyArray`, ref TValue[] `valueArray`)
�z��`keyArray`��`valueArray`�����������A�v�f���[���̔z��Ƃ���B

### UDict.Add<TKey, TValue>(ref TKey[] `keyArray`, ref TValue[] `valueArray`, TKey `key`, TValue `value`)
�z��`keyArray`��`valueArray`�ɁA�v�f`key`��`value`��ǉ�����B�������A����`key`�����ɑ��݂���ꍇ�͒ǉ�����Ȃ��B

### UDict.Remove<TKey, TValue>(ref TKey[] `keyArray`, ref TValue[] `valueArray`, TKey `key`)
�z��`keyArray`��`key`�̗v�f�ƁA���̑΂ƂȂ�z��`valueArray`�̗v�f���폜����B

## �擾���\�b�h

### TValue UDict.GetValue<TKey, TValue>(TKey[] `keyArray`, TValue[] `valueArray`, TKey `key`)
`keyArray`���������A`key`�̑΂ƂȂ�z��`valueArray`�̗v�f��Ԃ��B


# UQueue
Queue�̋@�\��񋟂���N���X�ł��B  
������`array`�ɂ�Queue�Ƃ��ĉ^�p����z��ϐ���ݒ肵�Ă��������B

## ���상�\�b�h

### UQueue.Initialize(ref T[] `array`)
�z��`array`�����������A�v�f���[���̔z��Ƃ���B

### UQueue.Enqueue<T>(ref T[] `array`, T `value`)
�z��`array`�̖����ɗv�f`value`��ǉ�����B

## ����^�擾���\�b�h

### T UQueue.Dequeue<T>(ref T[] `array`)
�z��`array`�̐擪�̗v�f���폜���A�Ԃ��B�������A��̏ꍇ�͂��̌^�̃f�t�H���g�l��Ԃ��B

## �擾���\�b�h

### T UQueue.Peek<T>(T[] `array`)
�z��`array`�̐擪�̗v�f��Ԃ��B�������A��̏ꍇ�͂��̌^�̃f�t�H���g�l��Ԃ��B


# UStack
Stack�̋@�\��񋟂���N���X�ł��B  
������`array`�ɂ�Stack�Ƃ��ĉ^�p����z��ϐ���ݒ肵�Ă��������B

## ���상�\�b�h

### UStack.Initialize(ref T[] `array`)
�z��`array`�����������A�v�f���[���̔z��Ƃ���B

### UStack.Push<T>(ref T[] `array`, T `value`)
�z��`array`�̐擪�ɗv�f`value`��ǉ�����B

## ����^�擾���\�b�h

### T UStack.Pop<T>(ref T[] `array`)
�z��`array`�̐擪�̗v�f���폜���A�Ԃ��B�������A��̏ꍇ�͂��̌^�̃f�t�H���g�l��Ԃ��B

## �擾���\�b�h

### T UStack.Peek<T>(T[] `array`)
�z��`array`�̐擪�̗v�f��Ԃ��B�������A��̏ꍇ�͂��̌^�̃f�t�H���g�l��Ԃ��B
