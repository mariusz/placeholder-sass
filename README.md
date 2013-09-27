# \_placeholder.sass

Simple mixin for styling HTML5 input `placeholder`. **Usage**:

    @include placeholder {
      color: red;
    }

Produces:

    ::-webkit-input-placeholder {
      color: red;
    }

    ::-moz-placeholder {
      color: red;
    }

    :-moz-placeholder {
      color: red;
    }

    :-ms-input-placeholder {
      color: red;
    }
