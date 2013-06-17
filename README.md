Web版Mutexです。
同一ページを開いた際にWebStorageイベントを検知して前ページが消える仕様です。

・動作確認ブラウザ
IE,Chrome,PC版Safari
・挙動がおかしいブラウザ
Firefox⇒前ページが消えずblankになります
モバイル版Safari⇒前ページが消えますが、その際にタブ移動が起こります
・動作しないブラウザ
Opera⇒window.closeアドオンを追加すると前ページが消えるようになります

